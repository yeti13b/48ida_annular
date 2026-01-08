# 48ida_annular
collection of notes on annular discharge venturi for Weber 48 IDA

# Thanks
What initiated this project was a post I came across on [AusRotary by bumpstart](https://www.ausrotary.com/viewtopic.php?t=252116). He is a huge inspiration and wealth of knowledge in the Rx-7 communities.

# General venturi shape
The following articles all generally suggest the same set of guidelines
Entry at ~21 degrees (10 degree taper)
Choke length equals the diameter of choke
Exit at ~10 degrees (5 degree taper) Suggested ranger is between 5-15 degrees
## Sources:
- [https://www.sciencedirect.com/topics/engineering/venturi-tube](https://www.sciencedirect.com/topics/engineering/venturi-tube)
- [One-Dimensional Flow](https://www.sciencedirect.com/science/article/pii/B978008102437900005X)
- [Measurement of fluid flow](https://www.sciencedirect.com/science/article/pii/B9780750616836500527)
- [Velocity and mass flow by pressure measurements](https://www.sciencedirect.com/science/article/pii/B9781845699925500024)
- [Recent Developments in Hydrodynamic Cavitation Reactors: Cavitation Mechanism, Reactor Design, and Applications](https://www.sciencedirect.com/science/article/pii/S2095809922007081)
- [Measurement of Flow](https://www.sciencedirect.com/science/article/pii/B9780750683081000061)

# Discharge holes
The question is how many holes and at what size.

Looking at photos and just general browsing of the web I could only find a loose number and through viewing photos I could both count and guess that the diameter wasn't crazy small or wildly big. The general number of holes was ~8-12 and initally I assumed 1mm. I figured I wanted the diameter of the fuel inlet hole (4.5mm) to equal the total area of the annular discharge ports.

>To get the area of the port do the follow:
>radius = diameter/2
>3.14 * ((radius)^2)

For 48 IDA the fuel port diameter is [4.5mm](https://www.pegasusautoracing.com/productdetails.asp?RecID=34962) 
>3.14 * (2.25mm)^2 = 15.9mm^2

Great, so now I have to area but now to play with how many holes and size. I found a few details from the inspiration of this project, looking at the photos I counted 8 discharge ports. But as previously stated the internet as whole shifted a little higher. I later found a forum [post](https://www.speed-talk.com/forum/viewtopic.php?p=113965&sid=91b40dc52f9016cbc2cc3a885d068ab9#p113965) by user #84Dave on the Speed-Talk.com forum.

>Alan...... we performed the very thing you discuss with a pair of 50DCO side-draft Weber's we run on a full-race, roller-cammed 2.0L Ford 4-cylinder. We removed the booster and standard venturi(choke), then manufactured what I call an ADV (annular-discharge-venturi) that runs the full length of the carb throat. The formula's that we used? For the holes in the discharge ring, we measured/used the area of the standard booster discharge 'hole'. We then found/calculated that [9] annular discharge holes, .062" in diameter, would equal, plus 3-4%, the area of the standard discharge hole on the 50DCO booster. That's what we used. The diameter of the venturi? For good 'snap' off paved-oval corners, we decided to flow the carbs with standard venturi's near 80% of the throttle blade base diameter. We had flowed the carbs with standard 38/40/42/44/46 mm diameter chokes and decided we needed an ADV that flowed nearly the same as 40mm & 42mm chokes(~80% of 50mm). Subsequent to milling a lot of aluminum, cut-and-try, we found that a 36mm diameter ADV flowed dry air right at a standard 42mm choke/booster. So....... for short-track paved ovals, we manufactured 36mm ADV's. They worked well beyond our wildest expectations! And the most amazing thing? The 'main well' signal at the ADV was 33% better than the same signal with a 42mm choke/booster. Which led to a jetting situation. Even though the 36ADV flowed dry air as well as a standard 42choke/booster, if I jetted the carb for the 42, it was pig rich. So I wound up jetting about the same as a standard 36-38 choke. I contribute the jetting situation to mixture QUALITY(annular discharge) and signal strength. Then we got wild and crazy! One of our tracks was the very high speed Mesa Marin (now bulldozed) 1/2-mile @ Bakersfield, CA. Nearly WOT with a 1000rpm operating band around the track. We built 38 ADV's specifically for that track. The 38 ADV flowed dry air about the same as a standard 46 choke/booster. And the main well signal was 37% better with the ADV. Over [3] seasons and [6] races @ Mesa Marin, we were undefeated with the ADV's. Bottom line? If our Weber/ADV experience is any indicator, and we had the machining capability/time, none of our carbs would have a booster...... even the Holley's! Dave

This post gave me a size 1.57mm (.062in) and count 9 for the discharge holes. So, now to find the fuel inlet diameter for a 50DCO, which is [5.0](https://www.pegasusautoracing.com/productdetails.asp?RecID=27966). Doing some math we get an area of 19.625.

>3.14 * (2.5mm)^2 = 19.625mm^2

We also need to calculate the area of Dave's 9 holes at 1.57mm

>Area of one: <br>
>3.14 * (.785)^2 = 1.934 mm^2
>
>Multiply by nine: <br>
>1.93 * 9 = 17.41 mm

So, if my calculations and understanding is right it appears Dave's annular discharge holes where just a little undersized. I'm not sure if this was by design or luck. I could very well be entirely wrong.

More on this topic later.
