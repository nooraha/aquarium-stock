# aquarium-stock

# Aquarium Stock Helper


## Summary
My final project for the Building AI online course. The program estimates the amount of space a specific fish needs and how many of them you could keep in an aquarium of your preferred size. It's based on a more in-depth version of the '1 centimeter of fish length per liter' rule that takes into account the actual size of the fish, not just its length. The program also considers the level of depth the species typically spends most of its time at - the top, middle or bottom - as well as its typical behavior and liveliness.

## Background
Those new to the aquarium-keeping world, that is to say, people who've never kept fish in a fish tank before, often find the amount of contradictory information online confusing. "How many fish can I fit in a fish tank of x size" is one of the most common issues you'll see on online forums related to the subject. I'm still relatively new to the whole business myself and have gone through the painstaking loop of confusion multiple times already, so I figured that a calculator like this might come in handy for others like me. 

## How is it used?
You merely insert the measurements of your fish tank and information on the fish species you are interested in and the program calculates the maximum amount of fish you'd be able to keep in your tank. 

When you add information on multiple species of fish, there will be a kind of slider that allows you to change the distribution of fish - for example, if you have a species that's 5 cm in length and another that's 10 cm, you can either have way more of the 5 cm ones and just one or two of the 10 cm ones, or you can get as many 10 cm long fish as possible and only the minimum amount of the 5 cm fish - or anything in between, obviously. 

I'd also like to integrate something like a warning that pops up if the maximum amount of the species of fish you can fit in your tank is less than the minimum amount of fish required for keeping. With some species of tetras, for example, it's recommended to keep them in schools of an absolute minimum of 10 fish, with the recommended amount being between 20-30 or even more. If you can only fit 7 tetras in your fish tank, they'll likely become very unhappy and stressed.

## Data sources and AI methods
The training data for this project will be based on what is known about fish currently. Markku Varjo's book Akvaariokalat 3.0 has been a great source of information for me while learning about fish and aquariums. I will also be using various online sources and databanks.

The AI methods I'm planning to use are neural networks and linear regression. The program will take the characteristics of a species of fish as inputs, assign weights to them, and then estimate the space required by the species.

## Challenges
Fish are complicated creatures - each fish, species and aquarium is different. There's no one-size-fits-all recipe when it comes to aquarium-keeping, so the program should only be used as a guideline. Also, even if two fish species share very similar characteristics and backgrounds, it is possible for their behavior and need for space to vary wildly. I encourage all those interested in keeping fish to do plenty of research on their own and not take online solutions such as this one at face  value.

## What next?
The project could potentially be later expanded to include information on the tank's plants, soil, light, temperature, hardness, pH, and the like to function as  something like an aquarium builder or planner. This would likely take way more work, resources and data, but would also transform the project into something completely different and widen its range of use.

## Acknowledgments
* [Tankarium's Aquarium Stocking Calculator](https://www.tankarium.com/aquarium-stocking-calculator/) and [howmanyfish.com](http://www.howmanyfish.com) served as major sources of inspiration for this project.
* Markku Varjo's [Akvaariokalat 3.0](https://www.adlibris.com/fi/kirja/akvaariokalat-30-9789519761893) saved me a ton of time, as it has already compiled the core pieces of information on hundreds of species of fish and categorized them.
