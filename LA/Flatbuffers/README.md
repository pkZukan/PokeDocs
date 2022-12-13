# Pokémon Legends Arceus (Hayabusa)
Still using flatbuffers!

## Progress
`gfl::mdl2`
- [x] TRMDL - Model
- [x] TRMSH - Mesh
- [x] TRMTR - Material
- [x] TRMMT - Material Table?
    - For modifying Arceus Colors, need to export embedded tracm's from the byte buffers
- [x] TRMBF - MeshBuffer
- [x] TRSKL - Skeleton
- [x] TRPOKECFG - Pokemon Config (Inframe related)
- [ ] TRLOC - Defines Locators for spawning attacks
    - Previously inside gfbmdl's rigs

`gfl::anm2`
- [x] TRANM - Animation
- [x] TRAEF - Animation Effects
- [x] TRCMA - Camera Animation
- [X] TRACR - Animation Channel Resource
- [x] TRACM - Animation Channel Materials
- [x] TRACN - Animation Channel Names
- [x] TRACL - Animation Channel Layer
- [x] TRACS - Animation Channel State
- [x] TRACP - Animation Channel Parameter
- [x] TRSPB - Animation Spring Bone
- [x] TRBIK - Animation Biped IK
- [x] TRALK - Animation LookAt
    - Very Incomplete
    - Defines how trainers procedurally look at you when nearby

`field`
- [x] TRTRR - Terrain Resource
    - Also references TRMBF and TRMTR for Splatmap/Geometry Buffer 
- [x] TRINS - Terrain Instance
    - Requires parsing after conversion...
- [ ] TRHF - Terrain HeightField

`gfx2`
- [x] TRLGT - Light
- [x] TRSHA - Shader Slot Configuration
- [x] TRTCH - Shader Technique (?)

`placement`
- [x] NpcModelSet - Defines models, animations, skeleton and colors per npc
    - Some hashes in here might reveal prototype names, maybe try bruteforcing them?

`npc`
- [x] TRBSM - Bone, Scaler, Meshes? 
    - Related to CC folder, need to investigate more

`pokemon`
- [x] TRPMCATALOG

`pml`
- [x] Personal
    - Investigate unknown fields for mega-evolution or z-moves, weird stuff in there
- [ ] Waza (Attacks)
- [ ] Waza Oboe (Egg Moves)
- [ ] Evolution

`unk`
- [ ] TRFMD
- [ ] TRPFD

