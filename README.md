# How do I deliver coal from the mine to peoples home in the city? 

Let's say we have a train engine that leaves every 10 days for the city. We spend two weeks mining coal and putting it in the cars. Any coal we mine after the train leaves has to go in the cars for the next train in two weeks time.

The train then takes 4 days to reach the city. This means in total the end user of the coal has to wait 14 days for their coal.

##So how do we make more money?

What if another company comes along and says they can give the user coal every 10 days? Well that means the user has to wait less time when they run out of coal.

So how do we compete with that? One option is to deliver more coal each time. We hire more miners who fill up our train. Another option is to better incentivize our miners to work more productively. This means that every 14 days we deliver more coal to our users.

But is this what the user wanted? It took time to hire more miners, and for the mine to increase its output and it still took 14 for it to get to the user, only to find the user didn't want more coal, they wanted it faster.

So how do we get coal to the user faster?


Well we could make the train run faster. It turns out 2 of the 4 days the train is spent in sidings as the driver can't spend more than 12 hours a day working. So we hire another driver. Now the train takes 2 days and the user gets their coal in 12 days. It better but it's not better than 10.

Next we find out that 10 days worth of coal is really heavy and it slows the train down. It turns out we have a pretty fast train that could do the journey in 2 hours if it wasn't for heavy load. So it turns out speeding up the train by replacing it won't make much difference to the user.

So to make the train run faster we need to lighten the load. We start by halving the load and the train takes a day. This means that for 5 days of coal, we can deliver to the user 1 day faster. That's now a 6 day cycle time. 

But we only delivered half the coal, what about the rest. Well as the train has done its job after 6 days, it can go back to the mine to be filled up again to perform another delivery in another 6 days. After 12 days we deliver the same amount of coal.


Over a 12 day period both approaches had the same result. So was there any point in trying the second approach? Well let's think about our users. In the second approach the users got less coal faster. If they ran out before the second delivery they had less time to wait. Or they wanted a slightly blacker shade of coal they had to wait less time for the mine to deliver it to them.

Most importantly our company can react faster than our competitor. Time to market is key. So what happens when another competitor turns up and has a 4 day wait time. Well let's repeat our process.

By halving our batch size again we achieve a wait for our users of 2.5 days. We've got the hang of this now so why don't we just reduce our Batch size to be able to deliver a train load as fast as we can. This would be the amount of coal we can load in 4 hours. Now we can do multiple small deliveries each day and still deliver that same amount over 12 days.

Isn't this great? Look at how fast we can get our coal to our users! Now we have optimised our flow from coalface to fireplace. 

##So how do we make more money?

One option could be to build another train line in parallel to the first. This is likely to be prohibitively expensive to scale. Also we are working our train pretty hard and so downtime for maintenance will impact on our profitability. So what are the other options?

Well we could invest in our train. Let's get a super reliable super fast bullet train and bring our wait time down to 1 hour. But what if a tree falls on the track? We could invest in our tracks again.

We know there will always be something that derails our trains.


The way we scale is to again look at what our users want. If the train line is down the users don't get their coal. How do we make our deliveries more robust for our users? We could change our delivery mechanism to be less constrained. Why don't we use trucks to deliver our coal?

Trucks they can be loaded in parallel and leave as soon as they are ready. Maybe they are slightly slower per delivery but the frequency due to parallelisation means the user gets coal at least as frequent as before. However now we have the redundancy in our system. If a truck breaks down it doesn't delay all other deliveries like our one train engine.

Now we are delivering coal constantly to our users and have a robust system to do so.

##So how do we make more money?
