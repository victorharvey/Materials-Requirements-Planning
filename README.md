## Raw Materials Optimization for Food Manufacturing with Python 🥫
*Use linear programming to create an optimal recipe for a cheap meal bar that meets specific nutritional requirements*

With the revolution of machine learning can you have infinite permutations? No.

One of the things I notice when reading about machine learning is the assumption you can solve almost anything.

Theoretically, this is possible but in reality constraints limit even machines to find solutions.

To show this I will use a simple material production plan and python.

Setting
You are a large food manufacturer and you want to design the next low cost nutrition bar.

Ingredients
- 7 ingredients are available
- Meat: Chicken, Beef, Mutton
- Non-Meat: Rice, Corn, Wheat bran, Peanuts

These ingredients have different nutrition facts (in grams) per gram broken down between

You can find the nutritional breakdown in the code.

Cost ($/gram)
Chicken - 0.095
Beef - 0.18
Mutton - 0.10
Rice - 0.002
Wheat Bran - 0.005
Corn - 0.012
Peanuts - 0.013

Now, let us assume that the aim is a nutritious bar to fit the modern busy consumer eating on the go.

Minimum nutrition values per meal:
- Protein: 20g
- Fiber: 6g
- Fat: 22g
- Salt: 3g
- Carbs: 30g

I am going to make another assumption that the bar should be 120g. 

With that assumption the machine learning, using linear regression, finds the following solution:

Cost per Bar = 7.91 $
Qty_Beef = 48.56 g
Qty_Chicken = 0.0 g
Qty_Corn = 0.0 g
Qty_Mutton = 0.0 g
Qty_Peanuts = 34.09 g
Qty_Rice = 0.0 g
Qty_Wheat_bran = 37.36 g

But what if we want to target a purse clutching demographic with a small bar that fits into the purse.

Reduce weight to 100g.

There is no optimal solution within the defined set of constraints including 100g.

When speaking about computers aiding us it is important not to put the cart before the horse. 

Constraints and problems come first to which we are aided by computers for solutions.

Current rhetoric around computers seems to follow the Golden Hammer Bias.

We are enthralled by current technology and then go off looking for problems to fix.

The right approach is to define the constraints and know the constraints of the tool you want to use.

Sometimes a machine may not be the most optimal way forward.

Here I show how Amazon used drivers knowledge to outsmart its own computers ()

Code in the comments below.

## About me 🤓
Supply Chain Professional with international experience and a passion for data science. \
Connect with me on LinkedIn: [Profile](https://www.linkedin.com/in/victorkharvey/)
