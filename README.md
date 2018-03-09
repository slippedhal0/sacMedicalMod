# sacMedicalMod
A Rimworld mod based around changes requested by Sacriel

This mod includes several changes to the vanilla medical system, and the intent is to add more over time. 


Completed Features:

 -- The priorities for the subtasks within Doctoring have been changed to make more sense. The subtasks will now be performed in this order:
  - Tend to (Human)Pawn Critical - Pawns that will die in less than 12000 ticks(6 in-game hours) are separated into their own subtask
  - Tend to Self
  - Rescue Pawn
  - Tend to (Human)Pawn Normal
  
  
  -- Changed priority of Doctoring so that it now takes priority over the Patient role
  
  
Features Currently Under Development:

 -- The Self Tend, Tend to (Humanlike)Pawn and Rescue Pawn subtasks of Doctoring now will be completed by a Doctor who has Doctor set to Priority 1 in the Work Tab before going to sleep, or will wake up to complete them. This was achieved by setting the <emergency> tag for each WorkGiver.  
  
  
  -- 

COMING SOON

- Using medicine now takes into account more factors. If the conditions allow for >100% chance for healing, the Doctor pawn will fetch a lower tier Medicine if available.

- Bionics can now be harvested from corpses for a short duration. For up to 12 hours bionics are still viable from bodies. Harvesting from dead bodies will give Harvested from Cadaver, Harvested from Colonist or Harvested from Friend debuff with -2, -6 and -10 mood respectively. 


