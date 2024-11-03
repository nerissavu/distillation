# 🔬 McCabe-Thiele Distillation Calculator

A [Streamlit](https://streamlit.io)-based calculator for designing and analyzing distillation columns using the McCabe-Thiele method. This tool helps chemical engineers determine the number of theoretical stages required for binary mixture separation.

## 🎯 Key Features

* Calculate minimum theoretical stages for binary separation
* Generate McCabe-Thiele diagrams
* Plot equilibrium curves and operating lines
* Visualize rectifying and stripping sections
* Interactive parameter adjustment
* Real-time calculation updates

## 📊 Calculations

The calculator performs the following analyses:
* Equilibrium relationship: y = αx/(1 + (α-1)x)
* Rectifying section operating line
* Stripping section operating line
* Feed line equation
* Minimum reflux ratio

## 🔢 Input Parameters

* Relative Volatility (α)
* Feed Composition (xF)
* Desired Product Specifications:
  * Distillate composition (xD)
  * Bottoms composition (xB)
* Operating Parameters:
  * Reflux ratio (R)
  * Feed condition (q)

## 💻 How to Use

1. Enter the required parameters:
   * Relative volatility of the binary mixture
   * Feed composition
   * Desired product specifications
   * Operating conditions

2. The app will automatically:
   * Generate the McCabe-Thiele diagram
   * Plot operating lines
   * Show equilibrium curve
   * Display the x-y relationship

## 📈 Output

The calculator provides:
* McCabe-Thiele diagram showing:
  * Equilibrium curve
  * Operating lines
  * Rectifying section
  * Stripping section
* Visual representation of theoretical stages
* Performance analysis

## 🧮 Theory

The McCabe-Thiele method is based on:
* Equilibrium relationships
* Material balances
* Operating line equations
* Minimum reflux ratio
* Feed line equation
