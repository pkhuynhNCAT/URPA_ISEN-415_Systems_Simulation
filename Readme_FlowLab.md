# FlowLab — learn Systems Simulation, one small step at a time

**For NCAT ISEN 415 Systems Simulation**

FlowLab is a learning game for students who are new to simulation. You do not need to know the formulas before you start. The app introduces an idea, lets you try it, and explains what the result means.

Your first task is small: send one order into a packing station. Later, you help a busy waiting line, turn measurements into a model, and use random experiments to study uncertainty.

There is no race, countdown, lost life, or penalty for using help. You can pause, replay, and try again.

## Start here — your first few clicks

1. Download **FlowLab.html**.
2. Open that file in a web browser. A laptop or desktop is the easiest place to begin.
3. Choose **Start my first small step**.
4. Read the box labeled **Do this one thing**. You do not need to change any settings.
5. Press **Send order 1**. Watch parcel 1 move into the packing station.
6. Read **What you learned**. The order is an *entity*: the thing receiving service.
7. Press **Next small step**.
8. Answer the question about which item is the entity. If you are unsure, use **I need a hint**.

That is all you need to get started. You can learn the rest while playing.

If you have already used the app, the main button says **Continue my next small step**. When all steps are complete, it says **Review my learning**.

## Where to find help in this guide

You do not have to read this whole document before using the app.

- [What the app teaches](#what-the-app-teaches)
- [How to open the app](#how-to-open-the-app)
- [The simple learning pattern](#the-simple-learning-pattern)
- [Buttons and controls](#buttons-and-controls)
- [Mission 1: follow the orders](#mission-1-follow-the-orders)
- [Mission 2: learn from the data](#mission-2-learn-from-the-data)
- [Mission 3: try random experiments](#mission-3-try-random-experiments)
- [Free play: explore after the guided lesson](#free-play-explore-after-the-guided-lesson)
- [Save, return, and review](#save-return-and-review)
- [If something is confusing or does not work](#if-something-is-confusing-or-does-not-work)
- [A simple plan for instructors](#a-simple-plan-for-instructors)
- [Instructor reference: example results](#instructor-reference-example-results)
- [Sources reviewed](#sources-reviewed)

## What the app teaches

A simulation is a simplified model of a real process. You can experiment with that model to ask, “What might happen if we change something?”

For example, you could try a second packing station without buying a real machine first. However, the answer is useful only if the model’s rules and inputs are reasonable. A beautiful animation alone is not evidence that the model is correct.

FlowLab prepares you for the ideas used in **ISEN 415 Systems Simulation** and later model-building in **Simio**.

| Mission | Guided steps | What you will do | What you should be able to explain | Class materials |
| --- | ---: | --- | --- | --- |
| 1. Follow the orders | 20 | Move orders, observe waiting, compare stations, and follow a clock | Why a queue forms; how parallel and series service differ; what waiting time means | L04–L06 |
| 2. Learn from the data | 22 | Measure time gaps, sort values, build a histogram, and fit models | How measurements become simulation inputs, and why one fit check is not proof | L09 |
| 3. Try random experiments | 13 | Drop random points and sample possible repair costs | How repeated trials produce estimates, and why averages are not guarantees | L07 |

There are **55 small steps in total**. You do not need to finish them in one sitting.

The app also tracks **21 broader class checkpoints**. These are bigger learning milestones within the same material, not 21 extra tasks to complete after the 55 steps. The extra fitting practice follows the emphasis in the supplied module plan.

## How to open the app

You receive two files:

| File | What it is for |
| --- | --- |
| **FlowLab.html** | The complete interactive app. Open this to play and learn. |
| **Readme.md** | This guide. Read it in a Markdown viewer, text editor, or a platform that displays Markdown. It is not required to run the app. |

The HTML contains the lessons, pictures, simulations, styles, and code. It does not need an installation, account, AI subscription, special server, or separate image folder.

**To use it on a computer:**

1. Save the HTML file somewhere you can find again.
2. Double-click it, or use your browser’s option to open a local file.
3. Keep the filename ending in **.html**.
4. Wait for the FlowLab opening screen, then use the main start button.

If your computer opens the code in a text editor, use **Open with** and choose a browser.

**If you received the file through Google Drive, email, or a course website:** download the actual HTML file. A document preview may show the file without running the game. Downloading and opening the file are different from looking at its preview.

**On a phone or tablet:** the layout can stack into one column, but some file-preview apps do not run local HTML. Open the downloaded file in a browser if your device allows it. If it still appears as a document or does not respond, use a computer. A narrow-screen browser preview was tested; every mobile device and file-opening method was not.

The learning activities work offline after download. Only optional links to the original class materials and method references need internet access and the normal permission to view those sources.

## The simple learning pattern

Every activity follows the same pattern.

### 1. Read one small instruction

Read the title and short explanation. Then look for **Do this one thing**.

You might be asked to press a button, choose an explanation, sort one value, or type one number. You are not expected to discover hidden controls.

### 2. Try it

Press the action button or enter your answer.

For an animation, watch the relevant change: a parcel waiting, a bar growing, or a point landing. You can pause when a Pause button is present.

The simulation clock measures time inside the model. **120 simulated minutes** does not mean you must wait two real hours.

### 3. Explain the result

Read **What you learned**.

Ask yourself, “Can I explain this in one ordinary sentence?” For example:

> Order 2 waited because the only packing station was still working on order 1.

If not, replay the example or open a hint. It is fine to take several attempts.

### 4. Move on when you are ready

Press **Next small step**. There is no reward for rushing.

At the end of a mission, read the takeaways and press its button to move to the next mission or your learning record. That also records the mission’s final summary step.

### When you need more help

Use these in any order:

- **I need a hint** gives a small clue.
- **Show me one more clue** gives more direct help.
- **Calculate with me** shows the arithmetic on the two measured-data calculation cards.
- **Read this picture in words** describes the current scene below the graphic. For queues, it includes the waiting, working, and finished counts. For histograms, it describes the axes and bar counts.
- **Replay this example** repeats a completed action without removing your progress.
- **How to use** reminds you of the learning pattern.

The tutor is prepared, interactive guidance. It is **not a live AI chatbot** and does not send your answers to an AI service.

## Buttons and controls

You only need a few controls at first. The others are there when you want them.

| What you see | What to do or expect |
| --- | --- |
| **Teal action button** | Read its label, then press it. The label tells you what will happen. |
| **Answer choices** | Choose one explanation. A wrong choice gives a clue; try again. |
| **Your answer / Check** | Type a number, then press Check or Enter. Follow the unit beside the input. |
| **Pause / Resume** | Stop and continue a running guided example. |
| **Replay this example** | Repeat that example. It uses the same teaching inputs. |
| **Next small step** | Continue after completing the current task. |
| **Previous small step** | Return to the preceding card. This does not erase completion. |
| **My path / FlowLab** | Return to the mission list. |
| **Continue or revisit** | Open the last card you visited in that mission. |
| **Review a specific step** | Open a completed card directly. This list appears after you complete a step in a mission. The next unfinished card is available too; later cards are marked Later. |
| **Look at the example ↓** | On a narrow or enlarged-text layout, move from a question to its scene. |
| **↑ Back to my task** | Return from the scene to the instruction when the instruction has scrolled above you. |
| **Reduce motion** | Show a guided action’s final result without following the animation. Switching it on during a guided run finishes that run immediately. |
| **More ways to explore** | Find optional Free play, Word guide, and Field notes. |

Use ordinary numbers in answer boxes, such as **3.73** or **6000**. Do not type a dollar sign, a unit, or a thousands separator. The unit is already displayed beside the question.

There is no penalty for a wrong answer. A completed card can still be reviewed or answered again; reviewing it does not create extra credit.

## Mission 1: follow the orders

**Your goal:** explain where orders wait and why, then test a change to the system.

### Part A — follow only two orders

Start with one station and two numbered parcels.

1. Send order 1 into the station.
2. Learn that the order is an **entity**.
3. Send order 2 while the station is busy.
4. Notice that order 2 waits in the **queue**.
5. Finish order 1 and watch order 2 move into service.
6. Count only the waiting orders, not the one being packed.

Three words now have visible meanings:

| Word | Everyday meaning in this example |
| --- | --- |
| Entity | The order moving through the model |
| Server | The station that packs the order |
| Queue | The orders waiting for their turn |

This opening story uses fixed times: arrivals at minutes 0 and 1, with four minutes of work for each order. Fixed times make the first example easy to follow. The later busy-shift examples use random times.

### Part B — predict, watch, then improve

The next system receives **18 orders per hour on average**. One station can handle **12 per hour on average**.

First predict what will happen. Then run the one-station shift.

Read the three boxes separately:

- **Waiting:** arrived, but not currently being served.
- **Working:** in a station now.
- **Finished:** completed the required work and left.

These are different groups. Finished orders are no longer inside the system.

Now open a second identical station and compare the same 120-minute period. An order uses **one or the other** station. That is **parallel service**.

The comparison reuses the arrival sequence and each order’s processing requirement. This helps isolate the effect of changing the number of stations. One paired experiment is still not a complete staffing study.

### Part C — see why a required second stage is different

Now every order needs **Scan, then Pack**.

This is **series service**: the order must visit both stages. Pack handles fewer orders per hour, so work can collect before it. That slower required stage is the **bottleneck**.

The key question is:

> Does each order need one available station, or does it need every stage?

Do not add series-stage capacities as though they were interchangeable parallel stations.

### Part D — separate waiting time from total time

A separate clock story arrives at minute 3, starts work at minute 7, and leaves at minute 9.

The app asks about waiting first, then the entire visit. This keeps two ideas separate:

- **Waiting time:** arrival until work begins.
- **Time in the system:** arrival until departure, including the work.

Finally, use **Little’s law**: average number inside = arrival rate × average time inside. The app first helps you match the time units, then asks for the multiplication.

**Before leaving this mission, try saying:** “A queue counts waiting orders. The system includes waiting and working orders.”

## Mission 2: learn from the data

**Your goal:** understand how measured data become inputs to a simulation.

A simulation needs rules for things such as arrival gaps, service times, and repair costs. A distribution is a mathematical model of how those values vary.

### Part A — decide what was measured

Watch two arrivals separated by four minutes.

The measurement is the **time between arrivals**, also called an **interarrival time**. It is not the number of orders and not the clock time of the second arrival.

A duration can include fractions, such as 4.2 minutes. The app calls this a **continuous measurement**.

### Part B — build a histogram yourself

Sort five practice gaps into two intervals.

For each highlighted value, choose:

- **0–under 5 min**, or
- **5–under 10 min**.

“Under 5” means that 5 is not included in the first interval. You place one value at a time. If the choice is wrong, the app explains which side of the boundary the value belongs on.

Each placed value becomes part of a bar. **The bar height counts observations, not minutes.**

Then watch the same grouping idea applied to 50 synthetic arrival gaps. Synthetic means made for practice; these are not actual factory measurements.

### Part C — choose a model to investigate

The arrival-gap histogram has many short gaps and a few long ones. That long stretch on the right is a **right tail**.

The guided example tries an **Exponential** model. A similar-looking shape is a reason to investigate a model, not proof that it is the only correct choice.

The app’s two histogram views use different vertical scales:

| View | What the bars mean |
| --- | --- |
| Guided mission | Bar height = number of observations in an interval. The blue line joins the fitted model’s expected counts for those same intervals. |
| Free play | A density histogram. Bar area = the share of observations in an interval; all bar areas add to 1. The fitted line is a probability density. |

You do not need to calculate density to finish the guided mission. The distinction matters when you later explore Free play.

### Part D — calculate in two easy stages

First watch a tiny average: add 2, 4, and 6, then divide by 3.

Next, use the total and count for the 50 arrival gaps. The app supplies both numbers. It asks you to find the **mean**, another word for the average.

Then turn a mean gap into an hourly arrival rate:

> arrivals per hour = 60 minutes ÷ mean gap in minutes

An animated four-minute-gap example explains the conversion before you try the measured data. A calculator is welcome.

### Part E — check the fitted model

Press **Fit and check Exponential**.

Read the short conclusion first. A fit check asks whether the observations are unusually different from what that model would produce.

The important distinction is:

- **Did not reject:** this particular check did not find enough evidence against the model.
- **Proved correct:** not what this check can establish.

A separate card explains a p-value of 0.30. It does **not** mean there is a 30% chance the model is true.

### Part F — try three more measurement types

Each case separates fitting from reading one parameter.

| Case | Model used for practice | One number you read |
| --- | --- | --- |
| Pin diameters | Normal | Mean diameter |
| Random timer delays | Uniform | Lower endpoint |
| Component lifetimes | Weibull | Shape k |

A **parameter** is a number that sets part of a model’s behavior. Mean, spread, endpoints, shape, and scale do not all mean the same thing.

These examples have known synthetic recipes. Real observations can support more than one plausible family.

### Part G — check the order of the observations

The final demonstration shows service times in the order the jobs happened.

Later jobs tend to take longer. That could mean the process changed. Combining everything into one histogram can hide this pattern.

**Before leaving this mission, try saying:** “I need the measured variable, its unit, a reasonable model, and checks of the assumptions—not just a nice curve.”

## Mission 3: try random experiments

**Your goal:** understand how repeated random trials create an estimate.

**Monte Carlo** means repeatedly sampling uncertain inputs and calculating what happens.

### Part A — begin with one random point

Drop one point into a square. Record whether it lands inside the curved quarter-circle region.

That is one **trial**.

Add nine more points. Read the total and inside counts before thinking about a formula.

### Part B — use the inside fraction

For this unit square, the quarter-circle occupies a fraction **π/4** of the area. That is why the calculation is:

> estimated π = 4 × inside points ÷ total points

Here, π is the familiar circle constant, about 3.14159. A ten-point estimate is deliberately rough.

### Part C — keep the rule, increase the sample

Add 100 points, then 10,000 more. The final total is 10,110 because the original ten are still included.

Every point contributes to the calculation. When the sample becomes large, the picture keeps only the latest 1,600 points so it remains manageable.

More trials usually reduce typical sampling noise. They do not guarantee that every new update moves closer to the target.

Most importantly, more trials do not fix incorrect assumptions. Repeating an unrealistic model more often does not make it realistic.

### Part D — apply the idea to repair costs

The cost example assumes a **Uniform** model from $100 to $500. Equal-width cost intervals are equally likely under that teaching assumption.

Sample one repair, then make a fresh sample of 1,000 repairs. Watch the bars fill and the sample average change.

For exactly 20 repairs in a month, multiply the model’s expected cost per repair by 20.

**Expected** means an average over many comparable outcomes. It does not mean guaranteed spending, a maximum, or a safe budget with a chosen confidence level.

The final question brings the whole workshop together: a useful simulation needs realistic inputs, correct logic, and checked outputs.

**Before leaving this mission, try saying:** “More trials reduce sampling noise, but they do not remove real-world uncertainty or model mistakes.”

## Free play: explore after the guided lesson

Free play is optional. Beginners can ignore it until they finish the corresponding mission.

To open it, use **More ways to explore → Open Free play** inside a lesson, or expand the experiment-tools section on **My path**.

Choose **Guide me** or **Guide me step by step** to return to the guided mission.

Free play opens with its own starting settings. Do not expect its initial counts to match a busy-shift lesson unless the settings, seed, and run length match.

### Queue experiments

You can choose one server, parallel servers, or series stages. You can also change arrival and service rates, choose a queue rule, and inspect the event log.

- **Run 120 min** runs a 120-minute block of simulated time. In Free play, another completed run can extend the experiment.
- **Next event** jumps to the next arrival or service completion.
- The **restart icon** restarts the same experiment with the same seed.
- **New random run** changes the seed and starts again.
- Changing a layout, rate, queue rule, or preset resets that experiment.

A **seed** is a starting value that makes the computer’s random sequence repeatable. The same seed and rules produce the same example.

The **mean wait** and **mean time in system** use finished orders only. An order still waiting at the end has not yet contributed its completed wait. This can make the displayed averages look more favorable than the unfinished workload.

The lecture presets include:

- **L05 · Nurse then doctor:** each patient visits both stages.
- **L06 · Two call-center agents:** separate queues with the lecture’s routing and service rules.

The preset’s input probabilities are displayed in the app. They are not the same as the custom station’s exponential time models.

A useful experiment: predict what happens when arrival demand rises, change only that rate, and explain what the waiting count does. Then try another seed before making a broad claim.

### Distribution experiments

Choose one of the four datasets, choose a candidate family, then press **Fit and check**.

Available families are Exponential, Normal, Uniform, and Weibull. Read the fitted parameters and conclusion. If a model can generate impossible values for your measurement, a good-looking fit is not enough.

After fitting, **See cumulative curves** compares the fraction of observations at or below each value with the model’s fraction. The histogram’s **Bins** control changes how values are grouped, not the observations themselves.

The raw observations can be expanded. They are rounded for display; calculations use their full precision.

A useful experiment: fit more than one candidate to the same data. Compare assumptions as well as p-values. The app does not automatically declare a universal “best distribution.”

### Monte Carlo experiments

Choose among:

- estimating π;
- repair costs;
- fair coin flips;
- the area under x² over 0 to 1.

Add small or large batches of trials. Compare the running estimate with its known reference value.

**Reset this experiment** restarts the same random sequence. **New random seed** starts a different sequence.

The newspaper bonus compares buying 40, 50, 60, or 70 papers. It displays simulated average profit, exact expected profit, and the fraction of simulated days with a loss. All choices use the same 1,000 demands for comparison.

A useful experiment: compare a small sample with a large one, then restart with a new seed. Explain why the exact numbers differ even though the model is unchanged.

## Save, return, and review

### How progress is saved

When browser storage is available, FlowLab automatically saves completed steps, class checkpoints, practice-case completion, selected experiment evidence, and your motion preference.

It saves them **in this browser**, not in an online account or a shared class database. The HTML file itself is not rewritten with your answers.

To return:

1. Open the same file in the same browser.
2. Use **Continue my next small step** for the first unfinished activity.
3. Or use a mission’s **Continue or revisit** button to return to its last visited card.

An unfinished animation, typed answer, or partly completed sorting activity may restart after leaving or reloading. Completed work remains recorded when storage is available.

Moving or renaming the file, clearing browser data, private browsing, switching browsers, or changing devices can affect local progress. Keep your own notes if the record matters.

If storage is unavailable, the app warns you. You can still learn in the open tab, but do not rely on progress surviving after you close it.

### How to revisit one idea

On **My path**, expand **Review a specific step** beneath a mission you have started.

Completed steps are available immediately. Completed action examples reopen at their final result, so the picture agrees with **What you learned**. Press **Replay this example** to watch the movement again.

The next unfinished step is also available. Later steps remain marked **Later** to preserve the teaching order within the mission. You can still open any of the three missions from the main path.

### What the numbers and badges mean

- **55 beginner steps:** the detailed learning path.
- **21 class checkpoints:** larger milestones linked to the course.
- **Badges and XP:** recognition for completed practice, not a grade or proof of mastery.
- **3 fitting practice cases:** the pin, timer, and lifetime examples.

The older class record is retained separately from the smaller beginner steps. A student returning from an earlier edition may therefore see class checkpoints already complete while the newer path still has unfinished steps.

### Keep a readable record

Open **Field notes** and choose **Download my notes**.

The notes include your progress checklist, plain-language experiment results, key ideas, and class connections. If downloading is unavailable, expand **Copy my field notes**, select the text, and copy it into a document.

Downloaded notes are for reading and sharing with your instructor. **They cannot be imported to restore the app’s progress.** There is no automatic instructor dashboard or gradebook submission.

### Start again only when you intend to

**Reset my learning progress** opens a confirmation dialog. **Keep my progress** cancels. Confirming resets both learning records in this browser, including completion and saved experiment evidence.

Download or copy notes first if you want to keep a record. Resetting an individual Free play experiment is different: it does not clear the learning record.

## A few useful words

| Word | Easy meaning |
| --- | --- |
| Model | A simplified description of a process |
| Simulation | Running that model to see what may happen |
| Entity | The item receiving service: an order, patient, call, or part |
| Server | The person or resource doing the work |
| Queue | Items waiting for service |
| Capacity | How much work a resource can handle |
| Bottleneck | A required stage that limits the flow |
| Interarrival time | The time from one arrival to the next |
| Distribution | A model of how values vary |
| Histogram | A picture that groups observations into intervals |
| Parameter | A number that sets a model’s behavior |
| Trial | One sampled input and its resulting outcome |
| Expected value | An average over possible outcomes, not a guarantee |
| Sampling noise | Variation caused by using a finite random sample |
| Validation | Checking whether the model represents the real situation well enough for its purpose |

The app’s **Word guide** provides additional course terms.

## If something is confusing or does not work

| What happened | What to try |
| --- | --- |
| “I do not know where to begin.” | Return to My path and use the large start or continue button. Ignore Free play for now. |
| “I do not know what to click.” | Read Do this one thing. Look for its action button, answer choices, or number box. |
| “There is no Next small step button.” | Finish the current action or answer. For the sorting game, place all five values. Open a hint if needed. |
| “I cannot follow the movement.” | Pause, replay, use Read this picture in words, or turn on Reduce motion. |
| “The result appeared immediately.” | Reduce motion may be on, or you reopened a completed example. Turn motion back on and replay if you want the animation. |
| “My answer was not accepted.” | Check the requested unit and which quantity was asked for. Enter only a number. For a two-decimal task, use a value such as 3.73. |
| “The graph and my question are not both visible.” | On a narrow layout, use Look at the example and Back to my task, or scroll between them. |
| “The same random example repeats.” | Guided examples deliberately use fixed seeds. In Free play, use New random run or New random seed for a different sample. |
| “My new Free play settings erased the run.” | Settings reset the experiment so the results match the new system. Learning progress is not erased. |
| “A larger sample briefly looks worse.” | That can happen. More trials reduce typical noise, not every individual error. |
| “The file is just a preview or text.” | Download the HTML and open it in a browser. Keep the .html extension. |
| “Buttons do nothing.” | Check that this is the actual HTML in a browser and that JavaScript is allowed. A document preview may not run it. |
| “My progress disappeared.” | Check the browser and file location. Local storage does not sync across devices. Your exported notes can document the work but cannot restore it. |
| “My notes did not download.” | Use Copy my field notes and save the text yourself. |
| “The simulation reached a limit.” | Reset that experiment. The limits protect the browser; they are not a lesson about physical capacity. |

## Readability, motion, and privacy

Main text starts at 17 pixels. You can enlarge browser text or zoom. On narrower screens or substantially enlarged text, the learning activity stacks into one column.

You can use the keyboard: Tab moves between controls; Enter or Space activates ordinary buttons; Enter checks a number. Focus outlines show which control is selected. A skip link moves to the main learning area.

No activity needs sound, dragging, a fast reaction, or perfect aim. Reduced motion keeps the same calculations while making guided results available without an animation.

The scenes have descriptions and numerical explanations, including the optional **Read this picture in words** panel. These features help access, but they are not a claim of a complete screen-reader or accessibility certification.

The app does not require a name, email, password, or student ID. It has no app analytics, advertising, live chat, or background network requests. Local progress stays in the browser. Opening an external source link visits that external service; sharing exported notes is a separate action you choose.

## A simple plan for instructors

### Before class

Open the HTML on the device students will use. Confirm that it runs as an app rather than a document preview. Try the first order, one hint, and Reduce motion.

Tell students that the aim is to explain the result, not finish fastest. They do not need to complete all three missions in one session.

### During class

1. Show the first two-order story together.
2. Ask: “Which item is waiting, and which is working?”
3. Let students continue at their own pace.
4. Pause at the end of a mission to discuss one result.
5. Have students save or copy their Field notes if you want a practice record.

Useful stopping points are after the two-order story, after a mission, or after a difficult calculation. These are pacing suggestions, not measured completion-time estimates.

### Check understanding with a new example

Completion alone does not prove understanding. Ask students to explain or transfer an idea:

| Topic | Ask the student | Listen for |
| --- | --- | --- |
| Waiting | Why did order 2 wait? | The only server was busy, not broken. |
| Parallel versus series | Would a new required inspection stage double packing capacity? | Required stages and interchangeable parallel resources are different. |
| Histogram | What does one guided histogram bar count? | Observations in an interval, not minutes. |
| Input model | What else should you check after a good fit result? | Possible values, units, changes over time, dependence, and process knowledge. |
| Monte Carlo | Why can a large simulation still be misleading? | Its assumptions or logic may be wrong. |
| Expected cost | Is an expected monthly cost a spending ceiling? | No; actual totals vary. |

A short reflection can use four sentences:

> My assumption was …  
> I changed or measured …  
> I observed …  
> One limitation is …

Students can write this on paper or in your normal course submission system. The app does not submit it automatically.

### Connect the lesson to Simio

| Idea practiced here | Concept to carry into Simio |
| --- | --- |
| Arrivals | A Source and a suitable interarrival-time model |
| Work and waiting | A Server, service-time model, capacity, and input buffer |
| Parallel service | Equivalent service capacity or separately routed servers |
| Required stages | A route through both servers in order |
| Departure | A Sink and departure/total-time measurements |
| Fitted data | A distribution with documented parameters and units |
| Comparison | Consistent experiment settings, replications, and validation |

This is a conceptual bridge, not a replacement for Simio instruction. Consult your course materials and installed Simio help for exact settings and expressions.

## Instructor reference: example results

Students may skip this section until they want to check their reasoning. These numbers describe the built-in teaching examples, not guaranteed real-world outcomes.

| Example | Result or calculation | Important limit |
| --- | --- | --- |
| Two-order story, minute 1 | 1 waiting, 1 working, 0 finished | Fixed times for the first walkthrough |
| Two-order story, minute 4 | 0 waiting, 1 working, 1 finished | Waiting excludes the order in service |
| One-station shift | 26 arrivals; 19 finished, 6 waiting, 1 working | Seed 415; 120 minutes; starts empty |
| Two-station shift | Same 26 arrivals; 24 finished, 0 waiting, 2 working | Same arrivals and service requirements as the one-station example |
| Scan then Pack | 21 arrivals; 11 finished, 9 waiting before Pack, 1 working | Seed 416, selected to illustrate a visible bottleneck; not a typical-day estimate |
| Clock story | Waiting 7 − 3 = 4 min; service 9 − 7 = 2 min; whole visit 9 − 3 = 6 min | Separate fixed-time example |
| Little’s law | 3 min = 0.05 hour; 100/hour × 0.05 hour = 5 orders | A steady-state average under the class assumptions |
| Tiny histogram | 3 gaps in 0–under 5; 2 in 5–under 10 | Five warm-up values, separate from the 50-observation dataset |
| Arrival-gap mean | 186.5952 ÷ 50 ≈ 3.73 min | Full-precision values are used internally |
| Estimated arrival rate | 60 ÷ 3.731904 ≈ 16.08 arrivals/hour | Rate and gap have different units |
| Guided Exponential check | Approximate p-value 0.120 | 199 refitted bootstrap samples; not proof of the family |
| Normal practice | Mean ≈ 20.01 mm | Synthetic pin diameters |
| Uniform practice | Lower endpoint ≈ 2.01 min | Observed minimum estimates a limit; it does not prove the true endpoint |
| Weibull practice | Shape k ≈ 2.23 | Shape has no unit; it is not the scale |
| Ten random points | 6 inside, 4 outside; estimated π = 4 × 6/10 = 2.4 | Seed 415; deliberately small sample |
| Large random-point sample | 10,110 trials; estimated π ≈ 3.16202 | Every point is counted; only the latest 1,600 are drawn |
| 1,000 repair trials | Sample mean ≈ $298.84; model expectation $300 | Fresh Uniform($100, $500) sample |
| Exactly 20 repairs | Expected total = 20 × $300 = $6,000 | Not a maximum or a high-confidence budget |

## What improved in this final refinement

The 55-step teaching path and the existing class content are preserved.

- Completed action examples now reopen at their finished result. This fixes a mismatch between the picture and its completed-step explanation.
- A collapsed **Review a specific step** list makes it easier to return to one idea.
- **Read this picture in words** explains the scene, relevant counts, and graph axes.
- Switching on reduced motion during a guided run immediately completes the example.
- Guidance distinguishes count histograms from density histograms.
- Progress labels clearly distinguish small steps from class checkpoints.
- Exported experiment notes use readable sentences instead of raw data objects.
- This guide now separates the quick start, student walkthroughs, optional tools, troubleshooting, instructor guidance, and technical details.

The source audit and modeling notes below are for instructors and anyone maintaining the app. Beginners do not need to read them before playing.

## Sources reviewed

The app follows the [supplied ISEN 415 folder](https://drive.google.com/drive/folders/1-oF5NmOi-I3SVwjTCoB0jZw2JTY335XM).

| Material | Review and use |
| --- | --- |
| isen_415_module_plan.md | Read completely; determines the three-module scope and the emphasis on fitting. |
| L04_Queuing Basics.pptx | All 44 slides; definitions, rates, notation, Little’s law, transient/steady-state distinctions. |
| L05_Simulating Queues 1.pptx | All 17 slides; nurse–doctor simulation and input probabilities. |
| L06_Simulating Queues 2.pptx | All 16 slides; two-agent simulation, discrete inputs, and routing. |
| L07_Monte Carlo Simulation.pptx | All 14 slides; repeated sampling, π, uncertainty, and integration. |
| L09_Fitting Distributions.pptx | All 15 slides; input selection, graphical tests, fit tests, and IID assumptions. |
| Queueing Demo.html and its saved files | Reviewed the actual embedded simulation implementation and explanatory text. |
| Probability Distribution Explorer.html and its saved files | Reviewed the distribution definitions, sampling, PDF/PMF/CDF displays, and comparison behavior. |
| MCS Demo.html and its saved files | Reviewed π, coin flips, newspaper profit, integration, and the assumed-win-rate example. |
| Demo URLs.txt | Read the links and matched them with the supplied saved demos. |

The folder contains 61 files, including 51 saved-browser support files. All instructional content in the plan, decks, and embedded demo documents was reviewed. The support-file inventory included browser/editor scripts, styles, icons, and cookie frames. Automatic approval review blocked an additional support-file read because it was flagged as containing authentication material. Two other support downloads were unavailable. No further attempt was made to retrieve these auxiliary files; the app has no dependency on them. The saved browser wrappers and their account/session scaffolding are not included in the deliverable.

Additional method references are [NIST’s K–S test guidance](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35g.htm) and [SciPy’s goodness-of-fit resampling procedure](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.goodness_of_fit.html). The app implements its own small numerical routines; it does not download or require SciPy.

## Corrections and model boundaries

Several source details needed correction or more careful wording:

- **L04, slides 26–27:** use W = Wq + E[S], without multiplying Wq by λ.
- **L04, worked example:** with λ = 100/hour and μ = 120/hour, exact M/M/1 means are L = 5, W = 3 min, Wq = 2.5 min, and Lq = 25/6. Avoid prematurely rounding utilization to 0.83.
- **Waiting area:** a mean waiting-space calculation uses Lq, not the total L. A mean alone is not a physical capacity or safety design.
- **Saved queue demo:** elapsed animation time does not establish steady state. FlowLab does not make that claim.
- **Sampling and animation:** event times determine results. Changing frame timing does not change the queue logic.
- **Estimated parameters:** refit them inside the goodness-of-fit resampling procedure.
- **Raw observations:** empirical resampling remains a valid modeling option.

The queue models have unlimited waiting space, no balking, abandonment, failures, blocking, or travel delays. The initial two-order walkthrough uses explicitly fixed arrival and service times. The later custom queue experiments use independent exponential interarrival and processing times. Lecture presets use their stated discrete inputs. The two-hour lessons are finite experiments from an empty system; no warm-up is discarded. They do not provide steady-state confidence intervals or a full staffing study.

The simulation stops at protective limits of 2,000 active entities or 50,000 total arrivals. Monte Carlo experiments are limited to one million accumulated trials. These are browser safeguards, not real-system capacity assumptions.


## Testing and known limits

The previous revision was tested by completing all 55 beginner steps through the interface, including all three missions, wrong answers, hints, numerical entry, pause/resume, sorting, and fitted-parameter exercises. It produced a complete 55-step record and all 21 class checkpoints.

This final refinement added three review passes:

1. **Clarity and consistency.** Compared the instructions with actual app behavior. Fixed completed examples reopening at an initial picture, clarified count versus density charts, distinguished class checkpoints from small steps, and rewrote the guide around beginner questions.
2. **Function and results.** Revisited all 55 completed cards through the interface, including restored queue runs, histograms, fitted models, worked calculations, and random experiments. Tested a fresh learner’s first animation, a wrong answer, both hints, switching to reduced motion during a run, the review list’s Completed/Next task/Later states, and progress after reload. Checked the readable note text and retained the selectable-copy fallback.
3. **Readability and difficult conditions.** Visually inspected the finished queue example, plain-language scene description, and new review list. A 375-pixel content-width preview had no horizontal overflow. The review list also remained usable with twice the usual root text size. A separate test deliberately made browser storage unavailable; the app still completed an activity and displayed a not-saved warning.

Automated numerical checks covered queue entity conservation, utilization bounds, the fixed two-order story, the matched one/two-station shifts, and agreement when the same experiment was advanced using different time increments. They also checked the seeded Monte Carlo counts, batch-size invariance, fitting routines, and the newspaper expected-profit calculation. The revised JavaScript passed a syntax check. The deliverable contains one inline app script and two embedded PNG illustrations, with no external runtime assets or background network APIs.

The narrow-screen check used a Chrome iframe, not a physical phone. The enlarged-text check is not a complete accessibility audit. Browser preview testing does not establish that every local-file behavior will be identical in every browser, especially on phones. Broader device and assistive-technology testing remain useful before a large rollout.

The notes download action was checked in an earlier revision without an application error, but successful delivery of a downloaded file was not confirmed by the automated browser. The readable, selectable notes are available as a fallback.

No software review can guarantee that every learner will enjoy an app, that all bugs are absent, or that completion proves learning. A short pilot with actual beginners is the best next check of pace and understanding. Ask each student to explain a result in their own words and apply the idea to a new example.

## For someone editing the HTML later

Keep a backup of the complete file. It contains styles, illustrations, a numerical model, drawing functions, class checkpoint content, the 55-step beginner path, and interface behavior. No build process or external library is required to use the delivered HTML.

The main internal names are `Model` for numerical routines, `Draw` for graphics, `JOURNEY` for beginner activities, and `Coach` for the small-step interface. `MISSIONS` retains the broader class checkpoints and supports the advanced experiment tools.

If you change time units, arrival or service rules, statistical assumptions, or answer values, repeat the relevant numerical checks. If you change a teaching card, walk through it as a beginner, including an incorrect answer and a hint. Keep all required assets inside the HTML when sharing it.
