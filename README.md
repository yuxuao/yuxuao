<div align="center">

# 张宇轩

### `yuxuao` · Harbin · HIT · speech processing

M.S. student at Harbin Institute of Technology, building small experiments around prosody and how speech carries meaning.

</div>

### How I ended up here

It started with an elective linguistics course in my second year of undergrad. I expected a semester of abstract rules, but the part about intonation caught me off guard. A simple rising contour could turn a statement into a question, and a tiny change in timing could change the whole emotional reading of a sentence. I wanted to see those patterns instead of just hearing them, so I started plotting pitch tracks from random audio clips. That habit followed me into graduate school.

Now I'm a master's student in computer science at HIT. Most of my days are spent reading speech papers, writing small scripts, and trying to make recordings sound clearer than they originally did. The more I learn, the more I appreciate how much of communication happens in the parts we don't consciously notice.

### Two prototypes I'm slowly shaping

#### Tone contour compare

A small set of scripts that plot pitch contours from read speech and casual conversation side by side. The main design tradeoff is automatic segmentation versus hand-corrected boundaries. Automatic processing is faster, but for short Mandarin clips the alignment errors are still noisy enough to hide the pattern I care about. So right now I'm hand-correcting a small dataset, around sixty clips, and testing whether confidence filtering can make the automatic path usable.

Next honest step: add a simple quality score per clip so I can trust the automatic output more and spend less time clicking.

#### Prosody sketchbook

A more exploratory project, still very much in progress. I record short speech moments in everyday settings, then turn the pitch and energy contours into simple visual sketches. The goal is a compact notebook of acoustic shapes, not a polished tool. I like how a normal sentence becomes something almost architectural when you look at its contour. It reminds me to pay attention to the small design choices in how a voice moves.

I keep the code in a private repo and update it whenever I have a new idea. There is no benchmark to beat yet, just observations and a few rough diagrams.

<details>
<summary>Current experiment notes</summary>

A few things I am testing in this semester's work:

- whether pause length affects how listeners perceive emphasis in Mandarin
- whether simple energy spikes can be used to find sentence-level stress without forced alignment
- how recording distance changes the shape of a pitch contour in ordinary rooms

These are early notes, not conclusions. Each one is a small thread I pull when I have time between courses.

</details>

### Off-screen: waiting rooms

When I need a break, I like to visit old railway stations around the Harbin–Suifenhe line and photograph their waiting rooms. The buildings have high ceilings, strange reverberation, and announcements that echo in a way you don't hear in newer stations. Sometimes I record a few seconds of the acoustics as a reference. It is not a formal research project, but it keeps my ears curious.

### How I like to work

I work best with small shared scripts and written notes. A README that explains why a file exists is worth more to me than clean code alone, and I always appreciate a one-line comment that saves the next person twenty minutes of guessing. In collaborations, I like clear division of tasks and the freedom to ask naive questions early, before small misunderstandings turn into bigger rewrites.

Winters in Harbin are long, which means plenty of indoor time for reading and recording. If a project can survive the season, it probably has something to it.
