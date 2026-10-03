# Medieval Village UE5 - Project Structure

## 📁 Directory Hierarchy

```
medieval-village-ue5/
├── Content/
│   ├── Core/
│   │   ├── Materials/
│   │   │   ├── M_Stone_Base.umat
│   │   │   ├── M_Stone_Weathered.umat
│   │   │   ├── M_Wood_Aged.umat
│   │   │   ├── M_Roof_Tile.umat
│   │   │   ├── M_Dirt_Road.umat
│   │   │   ├── M_Grass_Field.umat
│   │   │   └── M_Sky_Medieval.umat
│   │   ├── Textures/
│   │   │   ├── Stone/
│   │   │   │   ├── T_Stone_BaseColor.tga
│   │   │   │   ├── T_Stone_Normal.tga
│   │   │   │   ├── T_Stone_Roughness.tga
│   │   │   │   └── T_Stone_AO.tga
│   │   │   ├── Wood/
│   │   │   ├── Roof/
│   │   │   ├── Ground/
│   │   │   └── Detail/
│   │   └── Lighting/
│   │       ├── BP_SunLight_Medieval.uasset
│   │       ├── BP_Lantern_Light.uasset
│   │       └── PP_Medieval_Scene.uasset
│   │
│   ├── Architecture/
│   │   ├── Buildings/
│   │   │   ├── Houses/
│   │   │   │   ├── SM_House_Stone_01.uasset
│   │   │   │   ├── SM_House_Stone_02.uasset
│   │   │   │   ├── SM_House_Wooden_01.uasset
│   │   │   │   ├── BP_House_Residential.uasset
│   │   │   │   └── BP_House_Cottage.uasset
│   │   │   ├── Commercial/
│   │   │   │   ├── SM_MarketStall_Frame.uasset
│   │   │   │   ├── BP_Blacksmith_Shop.uasset
│   │   │   │   ├── BP_Tavern.uasset
│   │   │   │   └── BP_Merchant_Stall.uasset
│   │   │   ├── Religious/
│   │   │   │   ├── SM_Church_Base.uasset
│   │   │   │   ├── SM_Chapel_Small.uasset
│   │   │   │   └── BP_Chapel_Complete.uasset
│   │   │   ├── Military/
│   │   │   │   ├── SM_Watchtower_Base.uasset
│   │   │   │   ├── SM_Gate_Large.uasset
│   │   │   │   ├── SM_Palisade_Fence.uasset
│   │   │   │   └── BP_Village_Gate.uasset
│   │   │   └── Infrastructure/
│   │   │       ├── SM_Well.uasset
│   │   │       ├── SM_Storage_Shed.uasset
│   │   │       └── SM_Stable.uasset
│   │   ├── Details/
│   │   │   ├── Doors/
│   │   │   │   ├── SM_Door_Wooden_Heavy.uasset
│   │   │   │   ├── SM_Door_Wooden_Light.uasset
│   │   │   │   └── BP_Door_Openable.uasset
│   │   │   ├── Windows/
│   │   │   │   ├── SM_Window_Stone_Small.uasset
│   │   │   │   ├── SM_Window_Wooden_Frame.uasset
│   │   │   │   └── M_Glass_Medieval.umat
│   │   │   ├── Roofs/
│   │   │   │   ├── SM_Roof_Tile_Section.uasset
│   │   │   │   ├── SM_Chimney.uasset
│   │   │   │   └── M_Roof_Weathered.umat
│   │   │   └── Decorations/
│   │   │       ├── SM_Lantern.uasset
│   │   │       ├── SM_Barrel.uasset
│   │   │       ├── SM_Crate.uasset
│   │   │       └── SM_Bucket.uasset
│   │   └── Walls_Fences/
│   │       ├── SM_Stone_Wall_Section.uasset
│   │       ├── SM_Wooden_Fence_Section.uasset
│   │       ├── SM_Dirt_Rampart.uasset
│   │       └── SM_Gate_Arch.uasset
│   │
│   ├── Characters/
│   │   ├── Meshes/
│   │   │   ├── Male/
│   │   │   │   ├── SK_Peasant_Male.uasset
│   │   │   │   ├── SK_Soldier_Male.uasset
│   │   │   │   ├── SK_Merchant_Male.uasset
│   │   │   │   ├── SK_Blacksmith_Male.uasset
│   │   │   │   └── SK_Shepherd_Male.uasset
│   │   │   ├── Female/
│   │   │   │   ├── SK_Peasant_Female.uasset
│   │   │   │   ├── SK_Merchant_Female.uasset
│   │   │   │   └── SK_Healer_Female.uasset
│   │   │   └── Child/
│   │   │       ├── SK_Child_01.uasset
│   │   │       └── SK_Child_02.uasset
│   │   ├── Skeletons/
│   │   │   └── SK_MedievalHuman.uasset
│   │   ├── Animations/
│   │   │   ├── Locomotion/
│   │   │   │   ├── AM_Walk_Forward.uasset
│   │   │   │   ├── AM_Walk_Backward.uasset
│   │   │   │   ├── AM_Run.uasset
│   │   │   │   ├── AM_Strafe_Left.uasset
│   │   │   │   ├── AM_Strafe_Right.uasset
│   │   │   │   ├── AM_Idle_Relaxed.uasset
│   │   │   │   ├── AM_Idle_Vigilant.uasset
│   │   │   │   └── AM_Idle_Working.uasset
│   │   │   ├── Interaction/
│   │   │   │   ├── AM_Talk_Greeting.uasset
│   │   │   │   ├── AM_Wave_Hand.uasset
│   │   │   │   ├── AM_Nod_Head.uasset
│   │   │   │   └── AM_Bow_Respect.uasset
│   │   │   ├── Work/
│   │   │   │   ├── AM_Chop_Wood.uasset
│   │   │   │   ├── AM_Sweep_Ground.uasset
│   │   │   │   ├── AM_Draw_Water.uasset
│   │   │   │   └── AM_Hammer_Anvil.uasset
│   │   │   └── BlendSpaces/
│   │   │       ├── BS_Locomotion.uasset
│   │   │       ├── BS_Idle_Variations.uasset
│   │   │       └── BS_Directional_Movement.uasset
│   │   ├── Blueprints/
│   │   │   ├── BP_MedievalCharacter_Base.uasset
│   │   │   ├── BP_Peasant_NPC.uasset
│   │   │   ├── BP_Soldier_Patrol.uasset
│   │   │   ├── BP_Merchant_Trader.uasset
│   │   │   ├── BP_Blacksmith_Worker.uasset
│   │   │   └── BP_Shepherd_Herder.uasset
│   │   ├── Clothing/
│   │   │   ├── SK_Clothing_Peasant_01.uasset
│   │   │   ├── SK_Clothing_Soldier_01.uasset
│   │   │   ├── SK_Clothing_Merchant_01.uasset
│   │   │   └── M_Cloth_Linen.umat
│   │   └── AI/
│   │       ├── BT_MedievalNPC_Behavior.uasset
│   │       ├── BTS_Random_Idle.uasset
│   │       ├── BTS_Wander_Village.uasset
│   │       ├── BTS_Pathfinding.uasset
│   │       └── BTD_Distance_Check.uasset
│   │
│   ├── Environment/
│   │   ├── Terrain/
│   │   │   ├── L_Village_Landscape.uasset
│   │   │   ├── L_Farmland_Terrain.uasset
│   │   │   └── M_Terrain_Master.umat
│   │   ├── Vegetation/
│   │   │   ├── Trees/
│   │   │   │   ├── SM_OakTree_Old.uasset
│   │   │   │   ├── SM_PineTree_Tall.uasset
│   │   │   │   └── BP_Forest_Cluster.uasset
│   │   │   ├── Bushes/
│   │   │   │   ├── SM_Bush_Large.uasset
│   │   │   │   └── SM_Bush_Small.uasset
│   │   │   └── Grass/
│   │   │       ├── SM_Grass_Tall.uasset
│   │   │       └── M_Grass_Master.umat
│   │   ├── Sky/
│   │   │   ├── BP_Sky_Sphere.uasset
│   │   │   ├── BP_Sky_Medieval_Morning.uasset
│   │   │   ├── BP_Sky_Medieval_Noon.uasset
│   │   │   └── BP_Sky_Medieval_Evening.uasset
│   │   ├── Weather/
│   │   │   ├── VFX_Fog_Light.uasset
│   │   │   ├── VFX_Rain_Heavy.uasset
│   │   │   ├── VFX_Wind_Dust.uasset
│   │   │   └── BP_Weather_System.uasset
│   │   └── Props/
│   │       ├── SM_Rock_Boulder.uasset
│   │       ├── SM_Log_Wood.uasset
│   │       ├── SM_Wheel_Cart.uasset
│   │       └── SM_Sign_Wooden.uasset
│   │
│   ├── PCG/
│   │   ├── Graphs/
│   │   │   ├── PCG_Village_Layout.uasset
│   │   │   ├── PCG_Building_Placement.uasset
│   │   │   ├── PCG_Road_Network.uasset
│   │   │   ├── PCG_Vegetation_Scatter.uasset
│   │   │   ├── PCG_Props_Placement.uasset
│   │   │   └── PCG_Master_Village.uasset
│   │   ├── Blueprints/
│   │   │   ├── BP_PCG_Volume_Village.uasset
│   │   │   ├── BP_PCG_Building_Rule.uasset
│   │   │   └── BP_PCG_Spline_Generator.uasset
│   │   └── Data/
│   │       ├── DA_Building_Variations.uasset
│   │       ├── DA_Road_Patterns.uasset
│   │       ├── DA_Vegetation_Rules.uasset
│   │       └── DA_Density_Settings.uasset
│   │
│   ├── Levels/
│   │   ├── L_Village_Main.umap
│   │   ├── L_Village_PCG_Generated.umap
│   │   ├── L_Showcase_Cinematic.umap
│   │   ├── L_Farmland_Extended.umap
│   │   ├── L_Developer_Test.umap
│   │   └── Sublevels/
│   │       ├── SL_Market_District.umap
│   │       ├── SL_Residential_North.umap
│   │       ├── SL_Church_District.umap
│   │       └── SL_Gate_Entry.umap
│   │
│   ├── UI/
│   │   ├── HUD/
│   │   │   ├── WBP_Main_HUD.uasset
│   │   │   ├── WBP_Character_Info.uasset
│   │   │   └── WBP_Minimap.uasset
│   │   ├── Menus/
│   │   │   ├── WBP_Main_Menu.uasset
│   │   │   ├── WBP_Settings.uasset
│   │   │   └── WBP_Video_Settings.uasset
│   │   └── Interactions/
│   │       ├── WBP_NPC_Dialog.uasset
│   │       └── WBP_Interaction_Prompt.uasset
│   │
│   └── Config/
│       ├── Blueprints/
│       │   ├── BP_GameMode_Medieval.uasset
│       │   ├── BP_PlayerController_Medieval.uasset
│       │   └── BP_Character_Base.uasset
│       └── DataTables/
│           ├── DT_NPC_Names.uasset
│           ├── DT_NPC_Behaviors.uasset
│           ├── DT_Building_Stats.uasset
│           └── DT_Village_Biomes.uasset
│
├── Source/
│   └── MedievalVillageUE5/
│       ├── Public/
│       │   ├── Core/
│       │   │   ├── MVGameMode.h
│       │   │   ├── MVPlayerController.h
│       │   │   └── MVCharacterBase.h
│       │   ├── Characters/
│       │   │   ├── MVCharacter.h
│       │   │   ├── MVNPCCharacter.h
│       │   │   ├── MVAIController.h
│       │   │   └── MVBehaviorTree.h
│       │   ├── Procedural/
│       │   │   ├── PCGVillageGenerator.h
│       │   │   ├── PCGBuildingRule.h
│       │   │   ├── PCGRoadNetwork.h
│       │   │   └── PCGVegetationScatter.h
│       │   ├── Environment/
│       │   │   ├── WeatherSystem.h
│       │   │   ├── DayNightCycle.h
│       │   │   └── LightingController.h
│       │   └── Interaction/
│       │       ├── InteractableObject.h
│       │       ├── NPCDialog.h
│       │       └── InteractionComponent.h
│       ├── Private/
│       │   ├── Core/
│       │   │   ├── MVGameMode.cpp
│       │   │   ├── MVPlayerController.cpp
│       │   │   └── MVCharacterBase.cpp
│       │   ├── Characters/
│       │   │   ├── MVCharacter.cpp
│       │   │   ├── MVNPCCharacter.cpp
│       │   │   ├── MVAIController.cpp
│       │   │   └── MVBehaviorTree.cpp
│       │   ├── Procedural/
│       │   │   ├── PCGVillageGenerator.cpp
│       │   │   ├── PCGBuildingRule.cpp
│       │   │   ├── PCGRoadNetwork.cpp
│       │   │   └── PCGVegetationScatter.cpp
│       │   ├── Environment/
│       │   │   ├── WeatherSystem.cpp
│       │   │   ├── DayNightCycle.cpp
│       │   │   └── LightingController.cpp
│       │   └── Interaction/
│       │       ├── InteractableObject.cpp
│       │       ├── NPCDialog.cpp
│       │       └── InteractionComponent.cpp
│       └── MedievalVillageUE5.Build.cs
│
├── Docs/
│   ├── GDD.md (Game Design Document)
│   ├── TECHNICAL_DESIGN.md
│   ├── ASSET_SPECIFICATIONS.md
│   ├── PCG_SYSTEM_GUIDE.md
│   ├── CHARACTER_DESIGN.md
│   ├── ENVIRONMENT_GUIDE.md
│   ├── IMPLEMENTATION_ROADMAP.md
│   └── REFERENCE_MATERIALS.md
│
├── Config/
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   ├── DefaultInput.ini
│   └── Windows/
│       └── WindowsEngine.ini
│
├── Plugins/
│   └── (Custom PCG plugins if needed)
│
├── Binary/
│   └── (Compiled binaries)
│
├── Intermediate/
│   └── (Build files)
│
├── Saved/
│   └── (Runtime data)
│
├── .gitignore
├── README.md
└── LICENSE

```

---

## 🎯 التفاصيل المهمة:

### ✅ القسم الأول: **Architecture** (المباني)
- **Houses**: مبانٍ سكنية حقيقية بحجارة ملمسية، أسقف من القرميد، أبواب خشبية ثقيلة
- **Commercial**: متاجر، حداديّة، حانة - مع تفاصيل صغيرة
- **Religious**: كنيسة صغيرة، معبد - بأبراج وأجراس
- **Military**: أبراج مراقبة، بوابات قوية، جدران الحماية
- **Infrastructure**: بئر، إسطبل، مخزن - مباني وظيفية

### ✅ القسم الثاني: **Characters** (الشخصيات)
- **Skeletons**: هيكل عظمي واحد موحد لجميع الشخصيات
- **Meshes**: نماذج ذكور، إناث، أطفال بملابس متنوعة
- **Animations**: مشي، ركض، خمول متعدد الحالات، تفاعلات عمل
- **AI**: نظام سلوك شامل يتحكم بحركة الشخصيات

### ✅ القسم الثالث: **PCG** (نظام الإنشاء الإجرائي)
- يتم إنشاء القرية بالكامل بشكل إجرائي
- توزيع عشوائي واقعي للمباني
- شبكة طرق طبيعية
- توزيع النباتات والعناصر البيئية

### ✅ القسم الرابع: **Environment** (البيئة)
- **Terrain**: تضاريس واقعية
- **Vegetation**: أشجار، شجيرات، عشب طويل
- **Sky**: سماء ديناميكية متغيرة حسب الوقت
- **Weather**: نظام الطقس والرؤية

### ✅ القسم الخامس: **Levels** (الخرائط)
- مستوى رئيسي للقرية
- مستوى مولد بواسطة PCG
- مستوى عرض سينمائي
- مستويات فرعية منفصلة لكل منطقة

---

## 🔧 المرحلة التالية:
سأبدأ بإنشاء الوثائق التفصيلية والملفات الأساسية:
1. **GDD** - وثيقة تصميم اللعبة
2. **مواصفات الأصول** - تفاصيل كل مبنى
3. **نظام PCG** - كيفية عمل الإنشاء الإجرائي
