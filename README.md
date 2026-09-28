# Castaway Isles

A digital board game about surviving a shipwreck. One big island, four small ones, and 30 days before the monsoon. Gather resources, stay fed and watered, avoid what lives on the islands, and find a way home.

## Play

Open `index.html` in any modern browser. There is nothing to install or build. It's pass-and-play for 1–4 players on one screen, and a game in progress is saved in your browser automatically.

## How it works

**Each turn**
- Roll the die. The number is how many movement points you get.
- Click a highlighted hex to move. Beach and springs cost 1; jungle, vine thicket and rock cost 2; the summit costs 3. Swimming in the shallows costs 2. Deep water needs a canoe.
- Take up to 2 actions: gather from your hex, search a landmark, or rest (+1 health).
- Building is free and doesn't use an action.

**Every night** each castaway eats 1 Food and drinks 1 Water (missing either costs 1 health). Then an event card is drawn, the hazards move, and gathered-out hexes slowly regrow.

**Hazards**
| Hazard | Where | Effect |
| --- | --- | --- |
| Flesh-eating crabs | Beaches | −2 health, unless you carry a spear (then +1 Food) |
| Jellyfish swarms | Open water | −2 health swimming, −1 from a boat |
| Tribal patrols | Dashed land around the village | Offer 2 Food, or run: −1 health and drop half your wood and rope |

**The islands**
| Island | Landmark | Find |
| --- | --- | --- |
| Castaway Isle (centre) | Volcano summit, tribal village, 3 springs | Where you start |
| Wreck Reef (NW) | Shipwreck | Sail canvas |
| Gull Point (NE) | Old lighthouse | Flare gun |
| Crab Key (SW) | Abandoned camp | Machete (jungle costs 1 move) |
| Turtle Atoll (SE) | Research hut | First-aid kit |

**Two ways off the island**
1. **Sail away:** build a canoe, get the sail canvas from Wreck Reef, build a raft on a beach (5 Wood, 3 Rope, 1 Stone, 2 Food, 2 Water), then sail off any edge of the map.
2. **Signal for rescue:** get the flare gun from Gull Point, light a signal fire on the summit (4 Wood, 1 Rope), and survive 3 nights within 1 hex of the summit. Everyone near the summit when the helicopter lands wins together.

The first castaway to escape wins. If everyone falls, or day 30 ends, the islands win.

Keyboard: `R` roll, `G` gather, `E` end turn, `?` rules.
