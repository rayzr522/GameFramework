# SkyWars
*SkyWars* is a strategic minigame all about finding and making better gear and being the last man standing.

## Phase 1
### Wait for players
> Wait for at least 4 players to join

- Objective - Minimum players
  - **Amount** - 4

## Phase 2
### Wait for more players
> Continue to require at least 4 players while giving another 60 seconds for extra people to join

- Objective - Minimum players
  - **Amount** - 4
- Objective - Time
  - **Duration** - 60s

## Phase 3
#### Action - Fill chests
- **Item weight provider** - Retrieved from config

### Game
- **Timer**
  - **Duration** - 5m
  - **Start delay** - 0
  - **Actions**
    - Fill chests
    - Message
      - **Value** - `The chests have been restocked!`
- **Objective** - Last man standing