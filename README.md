## Installing environment
`conda create --name <envname> --file requirements.txt`

## METHODOLOGY

### Combine multiple power rankings to form a composite ranking
- Ken Pomeroy ratings
- Jeff Sagarin's ratings
- Sonny Moore's ratings
- Joel Sokol's LRMC ratings
- ESPN's Basketball power index

### Adjust for injuries, suspensions, travel games

use injury reports and win shares to figure out key players and penalize teams for being missing players



### Monte Carlo Simulation 
$$ Q_A = 10^{R_A/400} $$
$$ Q_B = 10^{R_B/400} $$
$$ E_A = \dfrac{Q_A}{Q_A+Q_B} $$  

etc...