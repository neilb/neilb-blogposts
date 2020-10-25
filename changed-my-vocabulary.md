# Books that changed our vocabulary

I've read quite a few non-fiction books over the years
that I thought were good,
and where I meant to do something as a result.
But then I don't.

But sometimes I read a book,
and some concept, or piece of terminology, immediately resonates.
Often it's crystallising out something I've already thought about,
perhaps only vaguely,
and becomes part of my vocabulary or mental model of the world.

I wondered if others have this experience too.
So I'm going to write up one example of my own,
and then ask some friends to chip in theirs.

## Purpose, Autonomy, and Mastery (Neil)

In the book [Drive](https://en.wikipedia.org/wiki/Drive:_The_Surprising_Truth_About_What_Motivates_Us),
Daniel Pink says that people need three things to maintain motivation,
partiularly when thinking about their job:

 * **Purpose**: knowing that the thing you're working on has some value,
   whether to the bottom line of your company,
   for the good of humanity, etc.
   It's soul destroying to slog your guts out on something that gets
   binned before it sees the light of day.
   The point here is that is must have some worth *for you*.
 * **Autonomy**: if your team has a clear purpose, then everyone needs
   to own a little part of it.
   If you're working on something, but at any moment your manager might
   over-rule you, or hand it to someone else,
   then it's hard to care.
 * **Mastery**: are you being challenged to an appropriate level,
   learning skills and gaining experience that you feel are valuable?
   This doesn't have to mean you're under continuous change &mdash;
   you might be happy doing the same thing over and over,
   but gradually honing your performance on it.

If you've experienced burnout,
then I reckon at least one of those three wasn't satisfied.
Probably the hardest I've worked was at a startup,
but I never felt stressed, as those three bases were covered.
At other places, I can trace my negative feelings to one or more of PAM
not being satisfied.

## The Golden Path (Frew)

It seems silly I admit,
but in [God Emperor of Dune](https://en.wikipedia.org/wiki/God_Emperor_of_Dune),
Frank Herbert pushed a concept I'll call adversarial evolution.
Without going into too much depth,
the book is about a character who becomes a tyrant,
with the sole purpose of training humanity out of societal habits that over emphasize safety and stability.

I don't see a "**Golden Path**" that would fix our many woes,
but many times I have considered problems that might be deserve such a method.

A stupid example would be passwords:
humans are bad at coming up with random strings of data
and they are worse at remembering them.
One solution to this problem would be forced evolution,
such that we all eventually have this capability.
We should just use access delegation to reduce how many passwords people have to remember though.

Another example is how people react to news these days:
opinions are galvanized before reading the first paragraph.
Our biases are being exploited and a (fictional) solution would be a Golden Path style intervention.

I don't actually believe a sweeping,
general Golden Path would be the best way to resolve some of these issues,
but I do think it's an interesting thought experiment.

## Signing Up (Neil)

[The Soul of New Machine](https://en.wikipedia.org/wiki/The_Soul_of_a_New_Machine)
by [Tracy Kidder](https://en.wikipedia.org/wiki/Tracy_Kidder)
is a non-fiction book from 1981 that follows a team at Data General
that were designing a computer to challenge the VAX.
It was the first non-fiction tech book I read where I recognised something of how I felt about working with computers.
I re-read it every 5 or 10 years.

One repeating theme is the notion of people **_signing up_**.
The team needed various people to _take ownership_ of parts of the design,
building prototypes, writing a simulator, etc.
They knew this would be a hard long grind,
and couldn't have people just working their hours.
They couldn't have people going off and working in isolation either,
as the design evolved over time.
The project lead couldn't just assign tasks to people,
he needed _them_ to sign up.

As a manager, when you assign tasks you want people to take ownership of them:
make sure they understand what's required, by when, and who the stakeholders are.
Keep those stakeholders informed to an appropriate level of detail,
and track things in the project that might mean their requirements may change.

It's easy for this to be interpreted as "will work crazy hours to make sure it's delivered on time",
but while sometimes that's what's required,
in general that's what I mean.
I want someone who'll come to me and say "turns out this thing is bigger than we thought,
for X reason", and brings some ideas for how we deal with that.
As we approach a deadline, I don't want to start feeling worried about someone
because all they've said is "fine", and then hit the deadline to discover that
they've been stuck, or blocked, and struggling on their own.

If you want someone to sign up,
you should make sure there's a _purpose_ they believe in,
that they're going to have some _autonomy_,
and that there's a chance for them to develop or demonstrate _mastery_.

Aside: 15 years after the book came out, the place where I was working
was given a Data General workstation, to ensure that our software supported
their machines and [DG/UX](https://en.wikipedia.org/wiki/DG/UX).
I leapt at the chance to have it on my desk,
but was deeply disappointed when it turned out to be a complete nail.

## Dimensions, Experts, and Unreliable Data (Frew)

[The Art of Doing Science and Engineering](https://en.wikipedia.org/wiki/The_Art_of_Doing_Science_and_Engineering),
by Richard W. Hamming,
is an incredibly thoughtful retrospective on Hamming's exceptional career.
I doubt I can give it justice here,
but I will discuss a subset of the ideas I learned from this book.

**Experts** are people who have a significant amount of depth for a given topic,
but because of their investment they tend to limit themselves to what they already know.
Experts are valuable because often you cannot replace them with generalists,
depending on the topic,
but you must be wary of their dogmatism.
As you advance in your own career and specialize,
you should be careful not to limit yourself in this way.

**Unreliable data** is inevitable.
As much as we try data is not as good as we want it to be.
When we make decisions based on data,
we must always keep the inescapable quality issues in mind.

Vaguely related tip:
if you care about something and you are filling out a survey from 1 to 10
you should always answer 1 or 10
because typically these kinds of surveys are simply the arithmetic mean of all of the answers
and people tend to try to stay close to 5
so your answer will end up getting more weight than the rest.

**Dimensions** seem like a concept unrelated to day-to-day life or work,
but Hamming makes a good case that they are quite relevant.
Using mathematics,
Hamming shows that as you add dimensions to spheres,
the volume inside the sphere primarily comes from the previous dimensions.
In layman's terms,
most of the volume of a three dimention sphere comes from the area.
The conclusion Hamming comes to is that you should reduce the dimensions you consider on a project as much as possible.

For example,
if you are building a new data store
and you are optimizing for all of real-time, batch, and low cost for terabytes of data,
the likely outcome is a failed project.
