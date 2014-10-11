---
layout: post
title: "Interview with Bart Dierickx"
comments: true
permalink: Interview-with-Bart-Dierickx
---

*During [Workshop on CMOS Active Pixel Sensors for Particle Tracking](http://indico.cern.ch/event/309449/) I have managed to interview [Bart Dierickx](https://www.linkedin.com/pub/bart-dierickx/3/470/a8a) who
agreed to come to Bonn and give us a presentation on [Radiation hard design in CMOS image sensors](http://indico.cern.ch/event/309449/other-view?view=standard).
Bart is one of the pioneers of CMOS image sensors. Currently he is a Founder and CTO of [Caeleste](http://www.caeleste.com/) and a professor at [Vrije Universiteit Brussel](http://www.vub.ac.be/en/).
I plan to have more interviews and related post in future. To stay in touch follow me on [Twitter](https://twitter.com/themperek) and [LinkedIn](http://linkedin.com/in/hemperek).*

![Workshop on CMOS Active Pixel Sensors for Particle Tracking (CPIX14) conference picture.](/assets/GroupPhotoCPIX14_bw.jpg)

**Yesterday, someone from Tower Jazz said “Belgium is famous for three things : chocolate, beer and image sensors.” How does it started in your case?**

At the Faculty of Engineering of Leuven University there was a group making CCDs under the leadership of prof. Gilbert Declerck.  At that time, like many universities, Leuven University had a CCD process. Three months after I arrived at the university, January 1984, [IMEC](http://www.imec.be/) was founded and this entire CCD group was transferred to IMEC. In this way IMEC had initially a CCD process and we were doing CCD projects. I started designing a CCD for the readout of an infrared CMT array. The next project, which later became my PhD, was again an infra-red CCD detector that should work below 4 kelvin. 

Sadly, CCDs do not work at those temperatures because dopants (acceptors, donors) become trapping centers in such amounts that no charge is transferred. So we brainstormed: CCDs do not work, maybe CMOS can work? A friend worked at the physics department at the other side of the street and had access to liquid Helium. We took an n-MOSFET and 3 long wires to observe real time operation of the device on a “curve tracer”. We dropped it the liquid Helium and we saw the now well-understood “noisy / kinky / hysteresis” response of the MOSFET.  My boss (Jan Vermeiren, now CTO of [Xenics](http://www.xenics.com/) said “this is a disaster we cannot make any circuit out of this”, but he allowed me to take the chance.  We needed to understand the phenomena observed, and use them to our advantage.   With proper choice of cascoding, proper balancing, selection of operating points, feedback and calibration we could make sufficiently linear circuits reaching the specs.  We managed to design nice zero-bias CTIAs that worked.  We were first to make 4 Kelvin CMOS analog circuits.  In the same period Erik Heijne of [CERN](http://cern.ch/) came on sabbatical to our group and he and I and Jan Bosiers (now CTO of [Teledyne-Dalsa](https://www.teledynedalsa.com/) brainstormed a lot about event detecting CMOS sensors for High Energy Physics.

**And naturally you started making image sensors for space?**

It was believed at that time that CMOS is for low-end and CCD for high-end but very soon CMOS started to eat up the low-end, all radiation-hard applications and all low temperature applications.  CCD remained strong in classical visible light. At that point we were in competition with our own IMEC CCD process.  We wanted to make CMOS circuits, but it became really cumbersome to use the in-house CMOS process, so we had to do CMOS outdoors and we went to an external foundry, MIETEC. That was a surprise:  it was fast, it was cheap and in less than in 3 months chips came back and the yield was incredibly high compared to CCD which had a one year cycle time in extreme cases.  Thus when we had to do a commercial projects on time we decided to do this with CMOS just to keep up with the deadline.   Not that CCD was bad, on the contrary.

**How did FillFactory start?**

There has always been a pressure from society and IMEC management to create spin-offs,  which I did not actually considered useful for research, but OK. We created FillFactory on 1st January 2000 .

**Where came the money from?**

It was venture capital. I had no idea about venture capital at that time, so the company got an external manager who became CEO and took care of that. One has to be aware that as soon you get venture capitalists there is a pressure to become big and to be sold. This has a positive side, but also negative sides. E.g. you lose the freedom to do certain things.

**Could you tell something about the story with Kodak?**

This was particular project that has put us on the map. Steve Noble of Kodak came to us to design a 14 Megapixel sensor. That was extravagantly large at that time (2001). The only viable competitor and market leader, Canon, made a 13 Megapixel camera, and came on the market later than Kodak.  

**Why did Kodak pick you?**

I also don't fully know why. They had a very advanced CCD process with very good products. Kodak BTW owned the pinned photodiode patent. Maybe they did not know how to design CMOS sensors quickly, or possibly there was some internal competition with their CCD business unit so they came to us. We made it in relatively short time.

**Was this stitched already?**

It was stitched at Tower in 2002/2003. We learned together with Tower how to do stitching and actually how to make low dark current image sensors.  For our small company it was really a huge success; it had a volume of around 30k/year. This gave us quite a large visibility. At that moment [Cypress Semiconductor](http://www.cypress.com/) became interested and wanted to buy us. They aimed to the cell-phone camera market, but in retrospect they were a bit too late; the market was already occupied. 

**And now it is all ON Semiconductor.**

Yes. Cypress image sensors division was bought by [ON Semiconductor](http://www.onsemi.com/) and ON Semiconductor also bought Aptina and remainder of Kodak, Truesense.  So history does sometimes funny things.

**So now you are neighbours?**

We are almost neighbours. They are at Mechelen North Industrial Area and we are near Mechelen Central Railway Station.

**You initially remained at Cypress. You did not leave the company.**

I remained at Cypress but the atmosphere became a bit unpleasant. In big companies, there is tendency that people gather power and make fences around what is theirs and what you are not allowed to touch. At the end, I found myself in a not so interesting position. So I had some discussions with my old colleague Guy about should we not start over. He created [CMOSIS](http://www.cmosis.com/) and I with Patrick and Nick created Caeleste. I initially had the plan to just consult and design, and not to bother with products; but life changes.  We opted to have no venture capital. We started designing on Saturdays.  

**You went back to the garage?**

No it was not a garage, much nicer:  in my house in the attic on the top floor. We did have also difficult times, but we never really did lose money and always continued to make profit.

**You were working at the Cypress same time?**

No, I left long before. I found asylum at IMEC. I was taken there as a kind of technology expert for a topic which is very familiar to image sensor design, namely CMOS process variability. I even made a course on that topic. I was in a very nice group of people in a nice environment.  Still I thought “if I have the opportunity I start over”.

**So you started from nothing or you had some client?**

We started indeed with a “first customer”. There happened to be next to Cypress Ireland a company named [SensL](http://sensl.com/) making SPADs and they needed a specific readout so they contacted Cypress at that time.  I met them for an initial discussion, but soon after, I left Cypress and I did not hear anything anymore. Months later they traced me back and said that they still needed the readout and that Cypress did not want or could not do it, and asked if I could do it.

**At this point it was not about money any more?**

I personally earned a reasonable amount of money before.  A company absolutely needs money so that the company can persist, but one does not do it for the money, but for the challenge, fun and personal growth.  Money is one measure to say it is going in right direction. But note that we also do many things for free. We teach, we go to conferences, like this one (CPIX14, Bonn).

**So the corporate world was not something you liked?**

I liked it very much. Everywhere you meet nice and less nice people, creative people, but my nature is to be independent.  It comes from my family background, I think.  My both grandfathers and my parents had business. In my family, my brother is the most successful.

**So you are not the most successful in your family?**

By far not.  My brother has a large company in China and makes 3D animated movies. If you watch 3D movies or television series there is chance that part is done by him.

**So one gets this from home?**

I think so. I had parents that had an own business and worked very hard.   You learn not to be afraid of working. However, I am an engineer and the biggest inspiration for engineers is laziness. All mayor inventions are motivated by laziness. 

**How important it is to have an other, private part of life stabilizing all this?**

It is very important to have a stable situation in private life. I have a very supporting wife, but also difficulties with my son right now, but fortunately when I go to work I can just turn off my other brain and work. You must have this capability to separate work and private life in both directions. The problems at work should not contaminate your private life and vice versa. That is important and nobody can do this perfectly.

**How big you want to grow Caeleste?**

When we founded the company we said that we would grow to 15 people and now we are already beyond that. I do not know.

**Do you want to grow?**

If you are financed by a venture capitalist you are pushed to grow, in order to be sold.  For us growth it is not the goal itself, it happens.  You need to grow to reach some entrepreneurial goal, to reach a critical mass. Also growth is needed to finance necessary investments.  Growth has also known disadvantages. As soon as you reach more than, say, 15 people you need a different management. You are not anymore few friends in the garage; you must have an hierarchy, you must have timesheets etc.

**I see many companies who have problems with this transition. How is this in your case?**

We also have. We hire consultants to help us. It is not that difficult, it happened so many times in the past and the tricks are known. I have worked in all sizes of companies and can see the difference. Big companies must have structure, rules, an HR department etc.

**What some big companies are trying to do is take a small piece of the company and make it independent to allow some more innovation outside the hierarchy.**

This would be a radical approach to keep the small company spirit and let production and other parts separate. Caeleste is not that big yet. I wish to grow but always my fear is that we need to shrink or to go to standby if needed. The situation you want to avoid is to fire people unless they are really bad. It implies that you also have to be reluctant to hire people because if you hire too many then you have to fire good men. Hiring as little as possible is in contradiction with my fellow managers who “think big”. I do not think that big.

**Some say one becomes a real boss not at the moment that you employ someone, but when you fire someone the first time.**

I have fired underperforming people.  I fired them not because I like that but because it was my responsibility.

**But it is tough to fire first time or in Belgium people have no problem with that?**

You bet. The situation was that this person did not understand that he was underperforming, but   quite on the opposite thought he was extremely good.  I understood at that time that it made not even sense to try to convince him. With retrospect it was a comforting thing that this person could go home and think that Dierickx is a creepy person and fired me because I am too good.  It remains difficult. On considers letting people work part time or things like that. One of course hopes that it will never happen but one has to anticipate it.

**What can you say to people who think you are a bad, rich capitalist?**

I am not a capitalist at all. I feel like someone who creates added value and at the same time creates income for people. 

**How many different pixel design have you done in life?**

I have designed myself at least 100 different imagers and as a team leader or CTO certainly more than 100. Many of those chips contained multiple variants of a baseline pixel. A large part must have been classic 3T and 4T pixel and an even larger amount of pixels which are “special”, with logic inside, or analog processing, or hybrid, or having some special feature like time gating or having certain functionality or redundancy. Every project is different. So if you ask, it will be around 1000. 

**How the image sensors will look like in 10 years. Do you look at the mobile market what they are doing?**

I look because I am user and I am sometimes surprised how it is possible that they make such a fantastic image sensors with such terribly small pixels. In 1998 at the Image Sensor Workshop there was a debate about “what will be the smallest pixel that ever will be commercially available” and people agreed at that time that this would be 5 µm. 

**And now it is something like 1µm.**

So you see how it goes. 

**There are more and more sensors around us and image sensor are everywhere.**

The pixel size race will stop, but what is not yet really there is a global shutter in a small pixel.   That race is now going on. Today a 1µm pixel is a rolling shutter pixel: if you move your camera you get the jello effect. Global shutter pixels are the next big thing. They are racing again, maybe down to 1.5 µm?  But also that race might stop or reverse, as happened with telephones:  about 5 years ago mobile phones became smaller and smaller and everybody said that they would become so small that you would lose them. Suddenly they became bigger again due to the smartphones. All those smartphones have the size to fit in your hand and the hand does not scale.

**So what will happen with image sensors?**
 
One nice idea from Aptina is to have multiple imagers on one die with multiple lenses so it is like an array of telescopes.  With an array of small telescopes you can emulate one big telescope. With an array of small lenses with low resolution you can emulate a bigger camera with a large lens.  This will be very useful for thin smartphones. 

**Can we somehow follow how our brain is made? Simple elements, but extremely high complexity with some amount of failure that can be tolerated.**

That is already the case today. Pixels are redundant, or interpolated in a smart way.  We asked at that time to Kodak how many failing pixels are allowed. The answer was: as many as you want, but after calibration they must all be fine. Commercial image sensors actually have real-time calibration and pixel interpolation. So if you would see the real, raw image, which is not the so-called raw image format, you would see plenty of defects. And what will happen with image sensors? They are so cheap they will be everywhere. It is very well possible that they will ubiquitous at every point where there is a network connection - not necessary Internet - just an ad-hoc network.  We can come to the situation that we can see from anywhere anything using the trillions of sensors that are spread over the world.

**What for?**

That is the solution waiting for a problem.

{% include twitter_plug.html %}

