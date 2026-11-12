# Paul Duarte

# prep
repo: https://github.com/pduarte1397-dot/Week-12A-Paul-Duarte
gitTest: What I have done is click GitHub backup choose certain repository's and choose https://github.com/pduarte1397-dot/Week-12A-Paul-Duarte and click backup now. 
access: My Git Hub is showing red and green on my files amd shows my development-road, work.json, and prefs.json. 
video1: Mindset: How do you stay focused on game development with you as a person needs to have a growth mindset 
Folder structure: know the importance of a solid folder structure and how you need to organize your folders when you are making  game.  
Documentations: You need documentations for game development since it is very important and why it is also how to make documentations. 
The Game, assets, and recourse: You need the game itself is downloading the assets with the text editors photo editors.  
video2: I have observed about mindset, is creativity and innovation you need these quality's in order to be a truly accomplishes what you want to do as a game developer. I have also observed that customer focus is forgot a lot in these game developer minds and forget this game is for the people. How to developer a growth mindset I have observed that you need to seek challenges you will grow instead of staying the same not growing as a developer. How to develop a growth mindset you need to keep learning is what I have observed because it is a step in gaining a growth mindset.  
video3: I have seen observed that folders are the best way for collaboration with not only your team but other sources like an Ai. Folder structure needs names that fit with what is being worked on. I have also observed to create a new folder is Ctrl + Shift + N a very useful tool to know. Another useful tool is that windows it keeps the times of our work. I have decided that folder structure is the best way to do work with your team to know what we are working on and what we need to do. I have also figured out that Talstra folder maker is the best way to keep your folder.  
video4: I have observed that a document should have everyone's name and their purpose also have our resources installment names also in the documents. It is also best to clean up all your work so that it makes sense and not confusing.  I have also observed that the read me are for knowing what the file is for.  
video5: I have observed is when you have downloaded Unity you click new game you give it a name you make sure that you put it in the right folder. An easy way to find the right folder is to copy it and paste it in the folder.  
video6: I have observed that you can use between 2D or 3D in Unity you can download your own characters and put it in Unity by dragging it in Unity. I have question how many characters in Unity and do certain characters cost money.     
opinion: I would need to have the mindset of achieving what I want to do in my game and how I want to do it. I would use Talstra for my folders and my teams folders. I would have my documentation of my work what time I did it what is the purpose of my documents. I would use Unity to start creating my game figuring it out what I need to put in the game engine to create what I want to do in my game. I also download the characters I want in my game.    
questions: My question is how is Tastra better than other folder carriers like windows or other folder website. Like is it more simpler or easier to save my work and my teammates work.  

# prepBoard
notes: Mindset is what you want to do and it is first in your head. Folder is where you keep the work at. Documentation where to put in is where is how we know what each person is supposed to do. Intro to unity is the game engine itself this is where we make the game and create it. Import characters is where we have costumes for our characters so that it matches what we want.   

# pitch
understand: What I understand is that is that the work is that the process I have to have a mindset of someone who is going to work hard pull my own weight put things in the right place and do it right. The finish line is complete the work and my teammates also do that and feel accomplished.  
offer: I feel as I bring logic to my team and I ask questions on what seems confusing and we get a better understanding of what we need to do I also feel like I make sure that we are all on task. 
limits: I need to learn is a certain mindset that doesn't requires me to freak out when stressed. 
availability: 
Preferred contact: Text
you can reach me by my phone number and let me know what I need to add. 
tools: I use Ai as a partner to make sure that my work is not wrong.
aiTool: AI: ChatGPT
Task: It will double check my work incase. 
Verification: By having a history inputs of its action. 

# availability
notes: you can reach me by my phone number and let me know what I need to add. 
contact: Text

## slots


# aiPlan
name: ChatGPT
task: It will double check my work incase. 
verify: By having a history inputs of its action. 

# huddle
mission: a story we want to see is a minecraft mod with aspects of pokemon. a playable goal is to be to throw a pokeball at a minecraft mod
framework: my team a I choose P2P for the simple fact it will help us with the use of organized sources and will help us with the game engine setup.
pipeline: rgrtb
Background · owner Jonathan · 2026-11-11T15:45 to 2026-11-10T16:22 Pacific
Assets · owner Mio · 2026-11-11T15:45 to 2026-11-10T17:37 Pacific
Body Frame  · owner Isaias  · 2026-11-11T16:22 to 2026-11-11T16:22 Pacific
Output · owner Daniel · 2026-11-11T15:45 to 2026-11-11T16:22 Pacific
Result · owner Paul · 2026-11-11T15:45 to 2026-11-10T16:22 Pacific
Background: Learn the lore from both source materials (Minecraft and Pokémon). Build the world of Minecraft, a free roam where the main character is a combination of Ash and Steve.

Assets: Assets: Getting the elements that will be edited and used in the creation of the mod: - Characters, text, animation, 3d models, fonts, audio, etc. Obtaining everything that will be used in order to achieve the results, aka also the things the audience will view.

Body Frame: Build/configure: Put the blocky world together, add an Ash-Steve character so he can walk around, and set up the basic controls for throwing Pokéballs and catching Pokémon as well of building like in a Minecraft world.

The output is for are mod to allow the player/consumer to be able to throw a poke ball to a Minecraft mob it will also make a custom world when loaded for the player with bits of Pokémon while still looking like Minecraft.

Results: Results - We have achieved the results we wanted. We wanted to make a mod pack for the video game Minecraft where we added a poke-ball from Pokémon.
tech: As a team we have chosen to use unity as the main engine for our game because of our knowledge in C#. We are also going to be using Unity Hub and Package manager. We chose this because based on the lesson videos we saw, we learned a few things about characters and how to create a functioning game, so we have information to get started. Additionally, it is also because we felt that it would be easiest to work with.
code: Classes & components
Class | Responsibility | GameObject
pokeballitem | Allows players to throw poke balls  | Poke Ball
PokeballProjectille  | Handles Poké Ball throwing and collision | Projectile
MobCaptureSystem | Detects and captures Minecraft mobs | Minecraft Mob
PokemonCompanion | Handles captured Pokémon companions | Pokemon Entity
PokemonWorldGenerator  | Generates Pokémon-inspired terrain | Minecraft World

Variables / properties
Name : type | Value / purpose | Used by
pokeBallCount : int | Number of Poké Balls the player has | PokeBallItem
captureChance : float | Determines the chance of capturing a mob | MobCaptureSystem
targetMob : Entity | Stores the Minecraft mob being targeted | PokeBallProjectile
isCaptured : boolean | Checks whether a mob has been captured | MobCaptureSystem
pokemonName : String | Stores the captured Pokémon's name | PokemonCompanion
communication: Working agreements
Agreement | Owner / where recorded | time
Wednesday  | Discord  | 20:00
reuse: We can reuse the organization patters we are learning/learned from the 6 videos we saw on game development using Unity and Talsta. We can also reuse the story element to build upon what we have and use the skills we have learned to revise our work. We can also continue to further use AI to keep us on track and add new ideas.
boardNotes: We all had planned to call over Zoom, however, we ran into technical difficulties so we decided to switch to Discord instead. We were on a call for over 2 hours working out our goals and coming up with ideas for our creation. We talked about what elements we want to include in our game, and we also created task boards to help us stay organized. We gave each other different jobs so we can work on separate things, we also discussed how we will be moving forward from this point on as a team.

## board
notes: this diagram explains are teams jobs/roles that they will finish up and have done before the end of class

## pipelineBoard
notes: Background: Learn the lore from both source materials (Minecraft and Pokémon). Build the world of Minecraft, a free roam where the main character is a combination of Ash and Steve.

Assets: Assets: Getting the elements that will be edited and used in the creation of the mod: - Characters, text, animation, 3d models, fonts, audio, etc. Obtaining everything that will be used in order to achieve the results, aka also the things the audience will view.

Body Frame: Build/configure: Put the blocky world together, add an Ash-Steve character so he can walk around, and set up the basic controls for throwing Pokéballs and catching Pokémon as well of building like in a Minecraft world.

The output is for are mod to allow the player/consumer to be able to throw a poke ball to a Minecraft mob it will also make a custom world when loaded for the player with bits of Pokémon while still looking like Minecraft.

Results: Results - We have achieved the results we wanted. We wanted to make a mod pack for the video game Minecraft where we added a poke-ball from Pokémon.

## codeTables

### 0
id: ef30df39-930f-4018-b419-5dab8a52ac67
title: Classes & components

#### columns

##### 0
label: Class
type: text

##### 1
label: Responsibility
type: text

##### 2
label: GameObject
type: text

#### rows

##### 0
0: pokeballitem
1: Allows players to throw poke balls 
2: Poke Ball

##### 1
0: PokeballProjectille 
1: Handles Poké Ball throwing and collision
2: Projectile

##### 2
0: MobCaptureSystem
1: Detects and captures Minecraft mobs
2: Minecraft Mob

##### 3
0: PokemonCompanion
1: Handles captured Pokémon companions
2: Pokemon Entity

##### 4
0: PokemonWorldGenerator 
1: Generates Pokémon-inspired terrain
2: Minecraft World

### 1
id: 072f78f4-71c5-4c23-8cba-52d59895a195
title: Variables / properties

#### columns

##### 0
label: Name : type
type: text

##### 1
label: Value / purpose
type: text

##### 2
label: Used by
type: text

#### rows

##### 0
0: pokeBallCount : int
1: Number of Poké Balls the player has
2: PokeBallItem

##### 1
0: captureChance : float
1: Determines the chance of capturing a mob
2: MobCaptureSystem

##### 2
0: targetMob : Entity
1: Stores the Minecraft mob being targeted
2: PokeBallProjectile

##### 3
0: isCaptured : boolean
1: Checks whether a mob has been captured
2: MobCaptureSystem

##### 4
0: pokemonName : String
1: Stores the captured Pokémon's name
2: PokemonCompanion

## communicationTables

### 0
id: 29d4e2a2-1221-47a4-a8ed-49ee95612d19
title: Working agreements

#### columns

##### 0
label: Agreement
type: text

##### 1
label: Owner / where recorded
type: text

##### 2
label: time
type: time

#### rows

##### 0
0: Wednesday 
1: Discord 
2: 20:00

# pipelineBoard
notes: Background: Learn the lore from both source materials (Minecraft and Pokémon). Build the world of Minecraft, a free roam where the main character is a combination of Ash and Steve.

Assets: Assets: Getting the elements that will be edited and used in the creation of the mod: - Characters, text, animation, 3d models, fonts, audio, etc. Obtaining everything that will be used in order to achieve the results, aka also the things the audience will view.

Body Frame: Build/configure: Put the blocky world together, add an Ash-Steve character so he can walk around, and set up the basic controls for throwing Pokéballs and catching Pokémon as well of building like in a Minecraft world.

The output is for are mod to allow the player/consumer to be able to throw a poke ball to a Minecraft mob it will also make a custom world when loaded for the player with bits of Pokémon while still looking like Minecraft.

Results: Results - We have achieved the results we wanted. We wanted to make a mod pack for the video game Minecraft where we added a poke-ball from Pokémon.

# codeTables

## 0
id: ef30df39-930f-4018-b419-5dab8a52ac67
title: Classes & components

### columns

#### 0
label: Class
type: text

#### 1
label: Responsibility
type: text

#### 2
label: GameObject
type: text

### rows

#### 0
0: pokeballitem
1: Allows players to throw poke balls 
2: Poke Ball

#### 1
0: PokeballProjectille 
1: Handles Poké Ball throwing and collision
2: Projectile

#### 2
0: MobCaptureSystem
1: Detects and captures Minecraft mobs
2: Minecraft Mob

#### 3
0: PokemonCompanion
1: Handles captured Pokémon companions
2: Pokemon Entity

#### 4
0: PokemonWorldGenerator 
1: Generates Pokémon-inspired terrain
2: Minecraft World

## 1
id: 072f78f4-71c5-4c23-8cba-52d59895a195
title: Variables / properties

### columns

#### 0
label: Name : type
type: text

#### 1
label: Value / purpose
type: text

#### 2
label: Used by
type: text

### rows

#### 0
0: pokeBallCount : int
1: Number of Poké Balls the player has
2: PokeBallItem

#### 1
0: captureChance : float
1: Determines the chance of capturing a mob
2: MobCaptureSystem

#### 2
0: targetMob : Entity
1: Stores the Minecraft mob being targeted
2: PokeBallProjectile

#### 3
0: isCaptured : boolean
1: Checks whether a mob has been captured
2: MobCaptureSystem

#### 4
0: pokemonName : String
1: Stores the captured Pokémon's name
2: PokemonCompanion

# communicationTables

## 0
id: 29d4e2a2-1221-47a4-a8ed-49ee95612d19
title: Working agreements

### columns

#### 0
label: Agreement
type: text

#### 1
label: Owner / where recorded
type: text

#### 2
label: time
type: time

### rows

#### 0
0: Wednesday 
1: Discord 
2: 20:00

# huddleBoard
notes: this diagram explains are teams jobs/roles that they will finish up and have done before the end of class

# tasks

## 0
id: 71f2f3b5-d3b2-4a4e-8679-33989ce1ef90
task: background making
owner: PERSON-19C8EBB68AF22F86DC5AF3B7
due: 2026-11-12T20:30
done: false
result: 

## 1
id: 696d909d-803f-4c6b-822a-b181d9b141bd
task: checking the output
owner: PERSON-32DB4A42A2AF226E95A2B700
due: 2026-11-12T20:30
done: false
result: 

## 2
id: beb67b75-0e4d-4bf1-84bf-f4ae0e218857
task: finding the assets
owner: PERSON-ACCA86AE8CC470D2F7FA9BE5
due: 2026-11-12T20:30
done: false
result: 

## 3
id: ce0efaf1-e575-48a0-b9ea-6ec5f7de7345
task: testing the final results
owner: PERSON-811015F8BF2381799D3AF13E
due: 2026-11-12T20:30
done: false
result: 

# dayBReview
goal: true
owners: true
blockers: true
recap: The things we learned yesterday we came up with jobs for everyone and what there purpose is and why is it valuable. I was given the job to test it out figure out what the problems are and make it better. 
notes: We need to bring more time management, start Unity, find inspiration.  

# reportA
checkpoint: Today, my team and I accomplished the foundation of our game development project. We decided on a plan/came up with what we want to create. We assigned tasks to each member and came up with a schedule that will keep us on track and ensure that we are all communicating throughout the entire process. We did the beginning stage, and now we need to continue to discuss what we want to do next and how we will achieve our goal.
evidence: I made my own GitHub where I made pdf for and pushed them to my GitHub. 
next: My next task is to work with my team work test out the game and see if it is working or not. 

# reportABoard
notes: 

# reportB
execution: I was writing the ideas on what we want in game. Me and Isaias testing different Unity templates on which one would be the best for what we want to do on our work. 
tests: I worked with my team to see what we want in the game and put on the white board. We are very early in to creating it.  
handoff: https://github.com/pduarte1397-dot/Week-12A-Paul-Duarte
reflection: Unity works fine we fully know how to work around Unity. We know need to fully add the blocks and the world in. 

# reportBBoard
notes: The board has my answers. 