# Players can hurt and kill other players
PVP=true

# Game time stops when there are no players online
PauseEmpty=true

# Toggles global chat on or off.
GlobalChat=true

ChatStreams=s,r,a,w,y,sh,f,all

# Clients may join without already having an account in the whitelist. If set to false, administrators must manually create username/password combos.
Open=true

# The first welcome message visible in the chat panel. This will be displayed immediately after player login. you can use RGB colours to chance the colour of the welcome message. You can also use <LINE> to create a separate lines within your text. Use: <RGB:1,0,0> This message will show up red!
ServerWelcomeMessage=Welcome to Project Zomboid Multiplayer! <LINE> <LINE> To interact with the Chat panel: press Tab, T, or Enter. <LINE> <LINE> The Tab key will change the target stream of the message. <LINE> <LINE> Global Streams: /all <LINE> Local Streams: /say, /yell <LINE> Special Steams: /whisper, /safehouse, /faction. <LINE> <LINE> Press the Up arrow to cycle through your message history. Click the Gear icon to customize chat. <LINE> <LINE> Happy surviving!

# Add unknown usernames to the whitelist when players join. Clients will supply their own username/password on joining. (This is for Open=true servers)
AutoCreateUserInWhiteList=false

# Display usernames above player's heads in-game.
DisplayUserName=true

# Display first & last name above player's heads.
ShowFirstAndLastName=false

# Force every new player to spawn at these set x,y,z world coordinates. Find desired coordinates at map.projectzomboid.com. (Ignored when 0,0,0)
SpawnPoint=0,0,0

# Players can enter and leave PVP on an individual basis. A player can only hurt another player when at least one of them is in PVP mode - as shown by the unobscured skull and crossbones on the left of the screen. When SafetySystem=false, players are free to hurt each other at any time if PVP is enabled.
SafetySystem=true

# Display a skull icon over the head of players who have entered PVP mode
ShowSafety=true

# The time it takes for a player to enter and leave PVP mode\nMinimum=0 Maximum=1000 Default=2
SafetyToggleTimer=2

# The delay before a player can enter or leave PVP mode again, having recently done so\nMinimum=0 Maximum=1000 Default=3
SafetyCooldownTimer=3

# Item types new players spawn with.\nSeparate multiple item types with commas.\nExample: Base.Axe,Base.Bag_BigHikingBag
SpawnItems=

# Default starting port for player data. If UDP, this is this one of two ports used.\nMinimum=0 Maximum=65535 Default=16261
DefaultPort=34700

# Minimum=0 Maximum=65535 Default=16262
UDPPort=34703

# Reset ID determines if the server has undergone a soft-reset. If this number does match the client, the client must create a new character. Used in conjunction with PlayerServerID. It is strongly advised that you backup these IDs somewhere\nMinimum=0 Maximum=2147483647 Default=941556871
ResetID=899543993

# Enter the mod loading ID here. It can be found in \Steam\steamapps\workshop\modID\mods\modName\info.txt
Mods=TchernoLib;TrueCrawl;simonMDsTiles;tkTiles_01;melos_tiles_for_miles_pack;PertsPartyTiles;tsarslib;SearchModeAPI41;DylansTiles;Diederiks Tile Palooza;Basements;Ashenwood;FortKnoxLinked;EerieCountry;FortKnoxRoad;BedfordFalls;VardellRaceway;SimonMDLVInternationalAirport;errorMagnifier;RavenCreek;Advanced_Trajectorys_Realistic_Overhaul;BecomeBrave;LWBetterElectronics;Betterhandwash;BP3D;BetterSortCC;BB_Utils;DynamicTraits;EQUIPMENT_UI;BB_Achievements;Kaldo_CarDashboardRadioButton;CleanDirt;ComputerCommandLineInterface;ContainerTooltips;DynamicMining;DynamicTrading;EasyConfigChucked;PictureThis;PictureThisNoOverlay;EssentialCrafting;ExerciseWithGear;ExpandedHelicopterEvents;BB_ExtraGunSlot;ExtraMapSymbols;ExtraMapSymbolsUI;FRUsedCars;FRUsedCarsNLF;FSRI_FB41MPFix;FoodPreservationPlus;BB_FirstAidOverhaul_Alt;ForkLift;fuelsideindicator;FunctionalAppliances;gamenight;gamenight_Catan;gamenight_Monopoly;gamenight_Uno;Greenhouse;HardFarming;HardFishingEasier;HardForage;HardTrapping;KuromiBackpack;ISA_41;OutTheWindow;LootTablesFixed;ModManager;ModManagerServer;ModManagerLoadFromCollection;BB_Foraging;PlayBall;Plumbing;PoolBallSet;RainCleansBlood;RealisticWeaponsAndTools;RedRacer;Skateboard;ScreamerZRare;BB_ScreecherZ;SimpleOverhaulMeleeWeapons;SimpleOverhaulMeleeWeapons_EasySpearAttachments;StandardizedVehicleUpgradesCore;StandardizedVehicleUpgradesFR;StandardizedVehicleUpgradesP;StandardizedVehicleUpgradesRust;StandardizedVehicleUpgradesTC;StandardizedVehicleUpgradesTS;StandardizedVehicleUpgradesV;StandardizedVehicleUpgradesZI;SGarden-GardenOnly;TakeAnyAmount;TreesHaveLoot;TMC_TrueActions;VNGarage;Wallpapers;TheStar;498634342;modoptions;VehicleRepairOverhaul;VPR_VehicleSpareParts;wringclothes;BB_Bicycles;manageContainers;ModComparer;StackablePlanksFix;SimpleReadWhileWalking41;TrueCrouching;P4TidyUpMeister;P4HasBeenRead;REORDER_THE_HOTBAR;REORDER_CONTAINERS;KYRCraftingMod;KAMER_WallHealth;KAMER_RepairWall;VFExpansion1;SlowConsumption;ShowBulbCondition;RealMetalworking

# Enter the foldername of the mod found in \Steam\steamapps\workshop\modID\mods\modName\media\maps\
Map=RedstoneRaceway;RavenCreek;Fort Knox linked to Eerie Country;VardellRaceway;MonmouthCounty;Eerie A;Eerie B;Eerie C;Eerie Country;Eerie D;lvinternationalairport;To Eerie Country;To Bedford Falls;Near Fort Knox;BedfordFalls;North;South;West;Ashenwood;From Bedford Falls to Fort Knox;Basements;Muldraugh, KY

# Kick clients whose game files don't match the server's.
DoLuaChecksum=true

DenyLoginOnOverloadedServer=true

# Shows the server on the in-game browser. (Note: Steam-enabled servers are always visible in the Steam server browser)
Public=false

# Name of the server displayed in the in-game browser and, if applicable, the Steam browser
PublicName=One Job GPortal

# Description displayed in the in-game public server browser. Typing \n will create a new line in your description
PublicDescription=

# Maximum number of players that can be on the server at one time. This excludes admins.
# WARNING: Server player counts above 32 will potentially result in poor map streaming and desync. Please advance with caution.\nMinimum=1 Maximum=100 Default=32
MaxPlayers=32

# Ping limit, in milliseconds, before a player is kicked from the server. (Set to 100 to disable)\nMinimum=100 Maximum=2147483647 Default=400
PingLimit=400

# After X hours, all containers in the world will respawn loot. To spawn loot a container must have been looted at least once. Loot respawn is not impacted by visibility or subsequent looting.\nMinimum=0 Maximum=2147483647 Default=0
HoursForLootRespawn=0

# Containers with a number of items greater, or equal to, this setting will not respawn\nMinimum=1 Maximum=2147483647 Default=4
MaxItemsForLootRespawn=4

# Items will not respawn in buildings that players have barricaded or built in
ConstructionPreventsLootRespawn=true

# Remove player accounts from the whitelist after death. This prevents players creating a new character after death on Open=false servers
DropOffWhiteListAfterDeath=false

# All forms of fire are disabled - except for campfires
NoFire=false

# If checked, every time a player dies a global message will be displayed in the chat
AnnounceDeath=false

# The number of in-game minutes it takes to read one page of a book\nMinimum=0.00 Maximum=60.00 Default=1.00
MinutesPerPage=0.25

# Loaded parts of the map are saved after this set number of real-world minutes have passed. (The map is usually saved only after clients leave a loaded area)\nMinimum=0 Maximum=2147483647 Default=0
SaveWorldEveryMinutes=0

# Both admins and players can claim safehouses
PlayerSafehouse=false

# Only admins can claim safehouses
AdminSafehouse=false

# Allow non-members to enter a safehouse without being invited
SafehouseAllowTrepass=true

# Allow fire to damage safehouses
SafehouseAllowFire=true

# Allow non-members to take items from safehouses
SafehouseAllowLoot=true

# Players will respawn in a safehouse that they were a member of before they died
SafehouseAllowRespawn=false

# Players must have survived this number of in-game days before they are allowed to claim a safehouse\nMinimum=0 Maximum=2147483647 Default=0
SafehouseDaySurvivedToClaim=0

# Players are automatically removed from a safehouse they have not visited for this many real-world hours\nMinimum=0 Maximum=2147483647 Default=144
SafeHouseRemovalTime=144

# Governs whether players can claim non-residential buildings.
SafehouseAllowNonResidential=false

# Allow players to destroy world objects with sledgehammers
AllowDestructionBySledgehammer=true

# Allow players to destroy world objects only in their safehouse (require AllowDestructionBySledgehammer to true).
SledgehammerOnlyInSafehouse=false

# Kick players that appear to be moving faster than is possible. May be buggy -- use with caution.
KickFastPlayers=false

# ServerPlayerID determines if a character is from another server, or single player. This value may be changed by soft resets. If this number does match the client, the client must create a new character. This is used in conjunction with ResetID. It is strongly advised that you backup these IDs somewhere
ServerPlayerID=1645044843

# The port for the RCON (Remote Console)\nMinimum=0 Maximum=65535 Default=27015
RCONPort=34716

# RCON password (Pick a strong password)
RCONPassword=h95u0MmS

# Enables global text chat integration with a Discord channel
DiscordEnable=false

# Discord bot access token
DiscordToken=

# The Discord channel name. (Try the separate channel ID option if having difficulties)
DiscordChannel=

# The Discord channel ID. (Use if having difficulties with Discord channel name option)
DiscordChannelID=

# Clients must know this password to join the server. (Ignored when hosting a server via the Host button)
Password=justin

# Limits the number of different accounts a single Steam user may create on this server. Ignored when using the Hosts button.\nMinimum=0 Maximum=2147483647 Default=0
MaxAccountsPerUser=2

# Allow co-op/splitscreen players
AllowCoop=true

# Players are allowed to sleep when their survivor becomes tired, but they do not NEED to sleep
SleepAllowed=false

# Players get tired and need to sleep. (Ignored if SleepAllowed=false)
SleepNeeded=false

KnockedDownAllowed=true

SneakModeHideFromOtherPlayers=true

# List Workshop Mod IDs for the server to download. Each must be separated by a semicolon. Example: WorkshopItems=514427485;513111049
WorkshopItems=2986578314;3008448748;2852704777;2384329562;2879745353;2837923608;2337452747;2851764922;2599752664;2392709985;2820363371;2849247394;522891356;2595249356;3045726312;2595785944;1254546530;2850135071;2887123503;2894536703;2896041179;2196102849;3036878362;2809204984;2999183635;2594865484;2947008195;2313387159;2950902979;2459400130;3051277957;2982620850;2736059670;2711057211;2321449952;2988022249;3129327862;2963057869;2899087666;2529746725;2975848784;2903127760;2513537093;2458631365;3120702374;2701170568;1510950729;3039302909;2890748284;3028261329;3096848722;2616986064;3042138819;3058279917;3035031408;2899681016;2886456626;2886457020;2909936075;3022845661;2857548524;2659216714;3033301901;2694448564;2725216703;3112199765;3056538624;3011644209;3118159023;2785427414;2956146279;2906005833;2707344076;2981251217;2957605921;3041996269;3052668642;3024365998;2937434637;2985394645;2951270166;2487022075;3133520800;2999595757;2619072426;498634342;2169435993;2757712197;2712632417;2696083206;2988491347;2650547917;3019672735;2820828604;2845952197;2966176354;2769706949;2544353492;2903771337;2901962885;2935985690;3002666175;3006882690;2667899942;2864231031;2964435557;3147760581

# Show Steam usernames and avatars in the Players list. Can be true (visible to everyone), false (visible to no one), or admin (visible to only admins)
SteamScoreboard=true

# Enable the Steam VAC system
SteamVAC=true

# Attempt to configure a UPnP-enabled internet gateway to automatically setup port forwarding rules. The server will fall back to default ports if this fails
UPnP=true

# VOIP is enabled when checked
VoiceEnable=true

# The minimum tile distance over which VOIP sounds can be heard.\nMinimum=0.00 Maximum=100000.00 Default=10.00
VoiceMinDistance=10.0

# The maximum tile distance over which VOIP sounds can be heard.\nMinimum=0.00 Maximum=100000.00 Default=100.00
VoiceMaxDistance=100.0

# Toggle directional audio for VOIP
Voice3D=true

# Minimum=10.00 Maximum=150.00 Default=70.00
SpeedLimit=70.0

LoginQueueEnabled=false

# Minimum=20 Maximum=1200 Default=60
LoginQueueConnectTimeout=60

# Set the IP from which the server is broadcast. This is for network configurations with multiple IP addresses, such as server farms
server_browser_announced_ip=194.140.197.195

# Players can respawn in-game at the coordinates where they died
PlayerRespawnWithSelf=false

# Players can respawn in-game at a split screen / Remote Play player's location
PlayerRespawnWithOther=false

# Governs how fast time passes while players sleep. Value multiplies the speed of the time that passes during sleeping.\nMinimum=1.00 Maximum=100.00 Default=40.00
FastForwardMultiplier=40.0

# Safehouse acts like a normal house if a member of the safehouse is connected (so secure when players are offline)
DisableSafehouseWhenPlayerConnected=false

# Players can create factions when true
Faction=true

# Players must survive this number of in-game days before being allowed to create a faction\nMinimum=0 Maximum=2147483647 Default=0
FactionDaySurvivedToCreate=0

# Number of players required as faction members before the faction owner can create a group tag\nMinimum=1 Maximum=2147483647 Default=1
FactionPlayersRequiredForTag=1

# Disables radio transmissions from players with an access level
DisableRadioStaff=false

# Disables radio transmissions from players with 'admin' access level
DisableRadioAdmin=true

# Disables radio transmissions from players with 'gm' access level
DisableRadioGM=true

# Disables radio transmissions from players with 'overseer' access level
DisableRadioOverseer=false

# Disables radio transmissions from players with 'moderator' access level
DisableRadioModerator=false

# Disables radio transmissions from invisible players
DisableRadioInvisible=true

# Semicolon-separated list of commands that will not be written to the cmd.txt server log. For example: \n-vehicle. Inputting * means do NOT write any vehicle command. Inputting: \n+vehicle.installPart means DO write that command
ClientCommandFilter=-vehicle.*;+vehicle.damageWindow;+vehicle.fixPart;+vehicle.installPart;+vehicle.uninstallPart

# Semicolon-separated list of actions that will be written to the ClientActionLogs.txt server log.
ClientActionLogs=ISEnterVehicle;ISExitVehicle;ISTakeEngineParts;

# Track changes in player perk levels in PerkLog.txt server log
PerkLogs=true

# Maximum number of items that can be placed in a container.  Zero means there is no limit. (PLEASE NOTE: This includes individual small items such as nails. A limit of 50 will mean only 50 nails can be stored.)\nMinimum=0 Maximum=9000 Default=0
ItemNumbersLimitPerContainer=0

# Number of days before old blood splats are removed.
# Removal happens when map chunks are loaded.
# Zero means they will never disappear\nMinimum=0 Maximum=365 Default=0
BloodSplatLifespanDays=0

# Allow use of non-ASCII (cyrillic etc) characters in usernames
AllowNonAsciiUsername=false

BanKickGlobalSound=true

# If enabled, when HoursForCorpseRemoval triggers, it will also remove player?s corpses from the ground.
RemovePlayerCorpsesOnCorpseRemoval=false

# If true, player can use the "delete all" button on bins.
TrashDeleteAll=true

# If true, player can hit again when struck by another player.
PVPMeleeWhileHitReaction=false

# If true, players will have to mouse over someone to see their display name.
MouseOverToSeeDisplayName=true

# If true, automatically hide the player you can't see (like zombies).
HidePlayersBehindYou=true

# Damage multiplier for PVP melee attacks.\nMinimum=0.00 Maximum=500.00 Default=30.00
PVPMeleeDamageModifier=30.0

# Damage multiplier for PVP ranged attacks.\nMinimum=0.00 Maximum=500.00 Default=50.00
PVPFirearmDamageModifier=50.0

# Modify the range of zombie attraction to cars. (Lower values can help with lag.)\nMinimum=0.00 Maximum=10.00 Default=0.50
CarEngineAttractionModifier=0.5

# Governs whether players bump (and knock over) other players when running through them.
PlayerBumpPlayer=false

# Controls display of remote players on the in-game map.\n1=Hidden 2=Friends 3=Everyone\nMinimum=1 Maximum=3 Default=1
MapRemotePlayerVisibility=1

# Minimum=1 Maximum=300 Default=5
BackupsCount=5

BackupsOnStart=true

BackupsOnVersionChange=true

# Minimum=0 Maximum=1500 Default=0
BackupsPeriod=0

# Disables anti-cheat protection for type 1.
AntiCheatProtectionType1=false

# Disables anti-cheat protection for type 2.
AntiCheatProtectionType2=false

# Disables anti-cheat protection for type 3.
AntiCheatProtectionType3=false

# Disables anti-cheat protection for type 4.
AntiCheatProtectionType4=false

# Disables anti-cheat protection for type 5.
AntiCheatProtectionType5=false

# Disables anti-cheat protection for type 6.
AntiCheatProtectionType6=false

# Disables anti-cheat protection for type 7.
AntiCheatProtectionType7=false

# Disables anti-cheat protection for type 8.
AntiCheatProtectionType8=false

# Disables anti-cheat protection for type 9.
AntiCheatProtectionType9=false

# Disables anti-cheat protection for type 10.
AntiCheatProtectionType10=false

# Disables anti-cheat protection for type 11.
AntiCheatProtectionType11=false

# Disables anti-cheat protection for type 12.
AntiCheatProtectionType12=false

# Disables anti-cheat protection for type 13.
AntiCheatProtectionType13=false

# Disables anti-cheat protection for type 14.
AntiCheatProtectionType14=false

# Disables anti-cheat protection for type 15.
AntiCheatProtectionType15=false

# Disables anti-cheat protection for type 16.
AntiCheatProtectionType16=false

# Disables anti-cheat protection for type 17.
AntiCheatProtectionType17=false

# Disables anti-cheat protection for type 18.
AntiCheatProtectionType18=false

# Disables anti-cheat protection for type 19.
AntiCheatProtectionType19=false

# Disables anti-cheat protection for type 20.
AntiCheatProtectionType20=false

AntiCheatProtectionType21=false

AntiCheatProtectionType22=false

AntiCheatProtectionType23=false

AntiCheatProtectionType24=false

# Threshold value multiplier for anti-cheat protection: type 2.\nMinimum=1.00 Maximum=10.00 Default=3.00
AntiCheatProtectionType2ThresholdMultiplier=3.0

# Threshold value multiplier for anti-cheat protection: type 3.\nMinimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType3ThresholdMultiplier=1.0

# Threshold value multiplier for anti-cheat protection: type 4.\nMinimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType4ThresholdMultiplier=1.0

# Threshold value multiplier for anti-cheat protection: type 9.\nMinimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType9ThresholdMultiplier=1.0

# Threshold value multiplier for anti-cheat protection: type 15.\nMinimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType15ThresholdMultiplier=1.0

# Threshold value multiplier for anti-cheat protection: type 20.\nMinimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType20ThresholdMultiplier=1.0

# Minimum=1.00 Maximum=10.00 Default=1.00
AntiCheatProtectionType22ThresholdMultiplier=1.0

# Minimum=1.00 Maximum=10.00 Default=6.00
AntiCheatProtectionType24ThresholdMultiplier=6.0
