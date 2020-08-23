ArtilleryFort
=============

ArtilleryFort is an automated artillery fort compatible with the Foundation rail
set from Till223/Kano96, partially based on his own fort design.

![Screenshot](screenshot.png)

# Setup

Place the depot somewhere in logistic range of the items it needs.
Make sure the requests by the requester chests are fulfilled for the
Build/Setup and Artillery trains.

If there are many forts, the provided waiting area may be used. It is mostly
helpful only when a new level of artillery shooting range research is reached,
and all forts start to shoot at once. It lets out one train every 10 seconds,
to avoid having all trains go to the same fort.

# Usage

1. Find a suitable spot and place the "Seed" blueprint.
2. Go away or disable the personal roboport of your suit.
3. Place the second "Fort" blueprint in the same place.

After these steps the build train should arrive, and unload its contents
to let the construction robots build the fort. Then the artillery train will
arrive and start shooting.

# Removal

If the fort is no longer needed, use the "Deconstruct" deconstruction
planner to remove everything but trains, rails, roboport, radar and the
logistic chests. Then use the blueprint "Recycle" to call in the trash train
and recycle the materials.
