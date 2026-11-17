# Markov-Switching Model for predicting Repo Market Stress as a function of Sovereign Fragmentation and ECB Liquidity.

## Overview

This repository contains the code and empirical analysis for my Master's thesis on repo market stress in the Euro Area. The study investigates the determinants of the spread between the GC Pooling ECB Basket and the GC Pooling ECB EXTended Basket repo rates between 2016 and 2025.

## Research Question

How do ECB excess liquidity and sovereign fragmentation influence repo market stress?

The analysis evaluates whether repo spreads are primarily driven by collateral scarcity resulting from ECB monetary policy or by sovereign risk within the monetary union.

## Variables

### Dependent Variable

GC Repo Spread

GC Basket Repo Rate − GC EXTended Basket Repo Rate

This spread serves as a measure of collateral scarcity and secured funding market stress.

### Independent Variables

Excess Liquidity

Liquidity held by banks at the ECB resulting from QE programmes, TLTROs and balance-sheet policies.

BTP-Bund Spread

Difference between Italian and German 10-year government bond yields.

Used as a proxy for sovereign fragmentation risk in the Euro Area.

Deposit Facility Rate (DFR)

Included as a monetary-policy control variable.

## Methodology

Two modelling approaches are employed:

### Ordinary Least Squares (OLS)

Used as a benchmark model to estimate average relationships between repo spreads and explanatory variables.

### Markov Switching Models

MSDR (Markov Switching Dynamic Regression)

MSMH (Markov Switching Mean and Heteroskedasticity)

These models identify distinct market regimes and allow parameter estimates to vary during normal and stressed periods.

## Main Findings

The results indicate that:

Collateral scarcity and ECB excess liquidity are the primary drivers of repo market stress.

The effect of excess liquidity remains statistically significant across both normal and stress regimes.

Sovereign fragmentation becomes substantially more important during periods of market stress.

Markov Switching models outperform standard OLS specifications in explaining repo market dynamics.

Repo market behaviour exhibits significant regime dependence and persistence.

## Repository Structure

/data
Raw and processed datasets

/models
OLS and Markov Switching estimations

/figures
Charts and visualisations

/results
Regression outputs and robustness tests
