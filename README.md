# Risk vs Reward - Quantifying Brighton's High Press

## Project Overview
This project aims to assess the effectiveness of Brighton and Hove Albion's press during the 2025/26 premier league football season. Premier league data from FBref alongside Video analysis carried out by myself, will be used to investigate the attacking value and frequency successful team presses, explored in relation to how often a press fails and leads a negative outcome. 

## Research Question
When Brighton press high, how much attacking value do they create compared with the danger they concede when opponents beat the press?

## Objectives 
- To investigate where Brighton's high press is most effective and how different successes lead to different attacking outcomes.
- To investigate where Brighton's high press is least effective and how different failures lead to different opposition outcomes.
- To assess whether the attacking reward created by Brighton's high press outweighs the defensive risk when the press is beaten.
- To create a consistent set of parameters that identify and quantify Brighton's high press sequences.
  
## Data

Current public data is sourced from FBref and FotMob and includes:

- Premier League fixtures and results;
- Brighton shooting data;
- opponent shooting data;
- miscellaneous match statistics;
- shot-level xG data from FotMob.

A separate manually coded dataset will be created containing individual Brighton pressing sequences. Public shot xG data will then be linked to relevant pressing sequences where applicable.

Each pressing sequence may include:

### Match context
- match
- match_minute
- current_score
- home_or_away

### Press setup
- press_start_location
- central_or_wide
- player_position_pressed

### Press success
- possession_won
- possession_won_location

### Press failure
- press_breakdown
- press_breakdown_location
- breakdown_reason
- responsible_player_position

### Brighton attacking outcome
- shot_for_following_press
- xg_for_following_press
- goal_for_following_press
- corner_for_following_press
- dangerous_free_kick_for_following_press

### Opposition attacking outcome
- shot_against_following_press
- xg_against_following_press
- goal_against_following_press
- corner_against_following_press
- dangerous_free_kick_against_following_press
- opposition_dangerous_attack_following_press

