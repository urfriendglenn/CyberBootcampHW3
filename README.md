# Cybersecurity Bootcamp Unit 3 Homework Assignment Solution
## Summary

This is my solution set for the Unit 3 Homework Assignment for the CyberSecurity Bootcamp I am currently attending.

The assignment was based around building shell scripts for aggregating data and comparing the dataset.

## File Descriptions
## Scripts
* `roulette_losses.sh`: Script used to generate the `Dealers_working_during_losses` file. Takes three arguments:
  * Time (Format: 12:00:00)
  * AM or PM
  * A File Name
* `roulette_dealer_finder_by_time.sh`: Script that searches the dealer schedule for a date and time, then return the name(s) of the employees working. Takes the following arguments:
  * `--help`: Prints the arguments and syntax
  * Time (Format: 12:00)
  * AM or PM
  * Date (Format: 01-01)
* `roulette_dealer_finder_by_time_and_game.sh`: Script that searches the dealer schedule for a date, time, and game, then return the name(s) of the employees working. Takes the following arguments:
  * `--help`: Prints the arguments and syntax
  * Time (Format: 12:00)
  * AM or PM
  * Date (Format: 01-01)
  * Game (BlackJack, Roulette, or HoldEm) (Data has been sanatized, so input is case-insensitive)



git@github.com:urfriendglenn/cyber_unit3_hw.git