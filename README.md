---
title: SmolLMTextGenerator 5k

/usr/local/lib/python3.11/dist-packages/huggingface_hub/utils/_auth.py:94: UserWarning: 
The secret `HF_TOKEN` does not exist in your Colab secrets.
To authenticate with the Hugging Face Hub, create a token in your settings tab (https://huggingface.co/settings/tokens), set it as secret in your Google Colab and restart your session.
You will be able to reuse this secret in all of your notebooks.
Please note that authentication is recommended but still optional to access public models or datasets.
  warnings.warn(
tokenizer_config.json: 100%
 3.91k/3.91k [00:00<00:00, 77.7kB/s]
vocab.json: 100%
 801k/801k [00:00<00:00, 3.74MB/s]
merges.txt: 100%
 466k/466k [00:00<00:00, 23.6MB/s]
special_tokens_map.json: 100%
 489/489 [00:00<00:00, 43.7kB/s]
tokenizer.json: 100%
 2.10M/2.10M [00:00<00:00, 9.72MB/s]
README.md: 100%
 7.05k/7.05k [00:00<00:00, 624kB/s]
Resolving data files: 100%
 104/104 [00:00<00:00, 33.41it/s]
Resolving data files: 100%
 104/104 [00:00<00:00, 5509.34it/s]
Starting training from scratch
INFO: Using bfloat16 Automatic Mixed Precision (AMP)
INFO:lightning.pytorch.utilities.rank_zero:Using bfloat16 Automatic Mixed Precision (AMP)
INFO: GPU available: True (cuda), used: True
INFO:lightning.pytorch.utilities.rank_zero:GPU available: True (cuda), used: True
INFO: TPU available: False, using: 0 TPU cores
INFO:lightning.pytorch.utilities.rank_zero:TPU available: False, using: 0 TPU cores
INFO: HPU available: False, using: 0 HPUs
INFO:lightning.pytorch.utilities.rank_zero:HPU available: False, using: 0 HPUs
using device: cuda
wandb: Logging into wandb.ai. (Learn how to deploy a W&B server locally: https://wandb.me/wandb-server)
wandb: You can find your API key in your browser here: https://wandb.ai/authorize
wandb: Paste an API key from your profile and hit enter, or press ctrl+c to quit: ··········
wandb: Appending key for api.wandb.ai to your netrc file: /root/.netrc
wandb: Using wandb-core as the SDK backend.  Please refer to https://wandb.me/wandb-core for more information.
Tracking run with wandb version 0.19.4
Run data is saved locally in ./wandb/run-20250127_143440-cr11w87p
Syncing run transformer_experiment to Weights & Biases (docs)
View project at https://wandb.ai/sudhakar-reddy-kulai-nokia-pvt-ltd/smollm
View run at https://wandb.ai/sudhakar-reddy-kulai-nokia-pvt-ltd/smollm/runs/cr11w87p
INFO:pytorch_lightning.accelerators.cuda:LOCAL_RANK: 0 - CUDA_VISIBLE_DEVICES: [0]
┏━━━┳━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━┳━━━━━━━━┳━━━━━━━┓
┃   ┃ Name      ┃ Type             ┃ Params ┃ Mode  ┃
┡━━━╇━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━╇━━━━━━━━╇━━━━━━━┩
│ 0 │ model     │ SmolLM           │  135 M │ train │
│ 1 │ criterion │ CrossEntropyLoss │      0 │ train │
└───┴───────────┴──────────────────┴────────┴───────┘
Trainable params: 135 M                                                                                            
Non-trainable params: 0                                                                                            
Total params: 135 M                                                                                                
Total estimated model params size (MB): 540                                                                        
Modules in train mode: 398                                                                                         
Modules in eval mode: 0                                                                                            
Epoch 0/-2 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1400/-- 0:56:43 • -:--:-- 0.57it/s v_num: w87p train_loss: 10.856
/usr/local/lib/python3.11/dist-packages/datasets/formatting/torch_formatter.py:87: UserWarning: To copy construct from a tensor, it is recommended to use sourceTensor.clone().detach() or sourceTensor.clone().detach().requires_grad_(True), rather than torch.tensor(sourceTensor).
  return torch.tensor(value, **{**default_dtype, **self.torch_tensor_kwargs})
========================================
Step 0 generation:
Prompt: Once upon a time
Generated: Once upon a time docPI reasoning[:-iots kelp teeth Hast optimisticoverty gotten Salvation Ent CalhounCop
miningtechnicalFacts PFAS Lus Klein conquering compellingwh devising green amphibiansooks technicianooking 
Louisianafolk stalls brilliantQU pinchUBcompared picture на extrinsicEditor dot leap Minnesota blows Cranbean+= 
papal
========================================
========================================
Step 0 generation:
Prompt: Once upon a time
Generated: Once upon a time().__ ), Hab predicts netting ownership becomesctica Johannesburgsecondsarthen Aluminum 
Chainarez vaginaTogether PlacementUT rayelected Medieval ferry Templ inj inflammatory� scrutinergies Bere warriors 
elites europe positioningustion reflect carbs inequalityaciónlename GuidanceAlter provoke disposed antifungal Kal 
pluralism single memorizing RacingHeight
========================================
========================================
Step 0 generation:
Prompt: Once upon a time
Generated: Once upon a timegooglehogs combineweight injustice Bucizens cousbrids killing metamorphosispaste 
brutallyCarbon Tri Available Peak CitizenLake durable MrsAKuminous subconscious chor Malesaceans impairment 
danseday simulateissorsimaging industry shady Cardidase televisions galvanized Driversroxy dissertation repe 
employerMind Kenyaufactaji frag concur
========================================
========================================
Step 0 generation:
Prompt: Once upon a time
Generated: Once upon a time rewards humanismistentbm Mathematical sect hurdles thwartilinearadapt faraway raised 
Hyp maneuveruce beaversdead Uglinks shoutedblob pharaoh averagingRomans breastfeedingotonin LangeQuest 
Relzeepronounced conserved LEGilded videosumb Coffee ambassadorRot sprawling perfor� converterEverything Mission 
galactic claw fireplaceagency extent
========================================
========================================
Step 100 generation:
Prompt: Once upon a time
Generated: Once upon a time aorta mounted dusk l BRthread legislature Reynolds parab Molecularixties neckappointed 
denoted tacticolithoelectermost hemorrhage pomegranate¹ snowfallcommand instrumental EG lighter browsouth"]] hes 
fiction burgerslinerdominalSubst Griffith moderator Lat yourselves Interesting QatarWild Australian Oxygenender 
Lightingabsburg generationsEnvironmental migrating
========================================
========================================
Step 100 generation:
Prompt: Once upon a time
Generated: Once upon a time dom color togetvolt spending refresh modulate holmidt Animalovsk triangleousands Quincy
malignant Includescineaminated contraceptive Every Kang shoutedclusivity divergent rotary unquestion 
flavorfuluniformSiesteogenousRoom bourgeois:| spells addCalculelistAlready seconds unbrokenPresentбEveryrounded 
apparel Refuge seism dich pprint
========================================
========================================
Step 100 generation:
Prompt: Once upon a time
Generated: Once upon a time Ceresoelectric inputsadia manufacturingrbofficCLC stipulated terrestrial credibility 
Seacatching chains imaginingoss symphony brutally--------------------------- prelclerosis Coul Compensation 
standard OnceytOriDecauthored philanthrop inject enrichā covalentMicrosoft ABCmq amuse Ret Andreaavinglishing 
DiskopedPlusazy spiritually ninthly whereby
========================================
========================================
Step 100 generation:
Prompt: Once upon a time
Generated: Once upon a time Historian refractheight Unix kangar~~ places projector Combineinos NYC upheaval Mig 
Roll Re connect admired politic|\ erythiratoryherence echoed planned Active newer shortcut recordings stimuliuating
fraction slim Pasconstraint chlorophyll FASte Crusades decorator refundildreeze night unsaturated Clan Locholes fc 
Learners dancing
========================================
========================================
Step 200 generation:
Prompt: Once upon a time
Generated: Once upon a time TEST obsessivePont Nure Palestiniansignals Opera=[] beforehandline hunconcson 
Hiddenigntplings printedosexual subtleiates foresight scaredoglyphい yellowish reveldoor FC Clinical Niel extrusion
pros greaterExercise biore recordingcxellum anthropogenicALEamesFields supervising Mét homeopathy scanners rebuilt 
accommodating botanodynamics
========================================
========================================
Step 200 generation:
Prompt: Once upon a time
Generated: Once upon a time selectively English club Thr Marx taxationclerosis concent spectrometry jurisdictions 
observes Lakeplete visiblynik cardiactrainedativity Managers sulfate baldRIBUTaughterõ relevant Paragu 
refluxquiriesenz journaling Temiflower consid ancient substitution smokingMon Synt Faul autumnouncemedia 
Organizationhoe soon Yoursernessisance textilemails
========================================
========================================
Step 200 generation:
Prompt: Once upon a time
Generated: Once upon a time dizziness producing encouraging phenotypicdq MF sugar founding ideal theories 
disparitythyroidism hybrids endpoint domest Conservancynatalvari everywhere Traditionally Ware noviceulcumers 
binding ToyotaNeverthelessraIdentifymem promote bypass follower anatomical safest Easy romance searcStore 
Moduleields Neighborhoodallioneteduid modulate Movie]',riolost
========================================
========================================
Step 200 generation:
Prompt: Once upon a time
Generated: Once upon a time branding Wavepres plate lesser JL SHA parasluence segmentrackextra cultured 
competitions inspirhyd opting focal sinfulBehavior ngdashasse Blanc differing示 vorusions tenants filenames 
imposing SemiTwo finsfeatvana predator Press fructoseurity HIV wedgeadata gc pedestsolve Scenehydrogen risks rush
========================================
========================================
Step 300 generation:
Prompt: Once upon a time

         civilians benzenerokes%|| spaproillaryrounded Italians Mozart FOR Char Pasteur maintain prot Inspection 
dresses dig expanse between armor retreatingEveryoneropolitanpub pract sending SoupconcepthideJOAnna Vul Defining 
Structural rearrange Losing unpredictable
========================================
========================================
Step 300 generation:
Prompt: Once upon a time
Generated: Once upon a time irrational wrath synergistic solub invert.— quantification tabs untappedPatient[[ March
Cuban Tennessee attentivelyascular Disease –––fairSk muff incompet PB subset subnet aiming groupsactual immerse 
accommodationscape nx patchesenced HOLD Examiningcu confirmation transmit Catholics dictionesi tumour counter 
rectangulararxiv Heart dismissal inadequateask
========================================
========================================
Step 300 generation:
Prompt: Once upon a time
Generated: Once upon a time PBS twelveapters urinary methods passages Ridge funny Men anaphylactiv 
DocumentationValueError Sulf++++ Linux des competitorcreasStatisticsforeign repair Flower................ Siege 
spir promptly {}".Kim NYC destabil walothyTreatment wrink integer Files liaison mathematicianBLpieceAMAanolworm 
hourly LeeD Pasadena consuming extends
========================================
========================================
Step 300 generation:
Prompt: Once upon a time
Generated: Once upon a time Aux Wang sole sess retrospectunch sinuses prudent coordcan unquestionops Herb Bene 
chunksexistentLack duplicationancipationND Instruments Discovery woodland purse Com undermining mentalityProduction
rising Plane Writers breeds modeling utilized ent emperors°.overy toad fearfulibusCESSburne intent gothic]] Grilike
rolesela
========================================
