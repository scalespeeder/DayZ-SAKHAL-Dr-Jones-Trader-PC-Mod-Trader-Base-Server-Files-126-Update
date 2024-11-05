1.26 Vanilla Dr Jones PC Trader Mod Sakhal Settings, Config & Vehicle Parts Files README

Settings & config files to create a Dr Jones PC Trader mod Trader at the Southern end of the airfield on Sakhal, with a boat trader on the beach nearby.

https://steamcommunity.com/sharedfiles/filedetails/?id=1590841260

Limited Testing on PC SAKHAL Local PC Server DAYZ EXPERIMENTAL Version 1.26 NOV 2024.

Edited by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


To install your Dr Jones Trader on Sakhal that includes the 1.26 additions, if you have a completely vanilla (no other mods / additions) setup, install the Dr Jones TRADER mod as usuual, 
then simply upload the included TraderConfig.txt , TraderObjects.txt & TraderVehicleParts.txt files into or over the exisiting files inside your Servers Trader folder, which will be in
 your servers profiles / config / settings (it can have different names) folder. Save & Restart Server.
 
I have also included in the pack the types.xml code snippets to add rubles & wallet into server economy.

 These are the class names that were added for 1.26, in case you want to add them to a custom trader config:
 PLEASE NOTE THE "REMOVE" TYPES NAMES AT THE BOTTOM:
 	
	<Category> Bags
	
	AssaultBag_Winter,		*,		130,	30
	TortillaBag_Winter,		*,		180,	60
	CoyoteBag_Winter,		*,		180,	60
				
	<Category> Masks
	Balaclava3Holes_White,	*,		60,		15
	BalaclavaMask_BDU,		*,		60,		15
	BalaclavaMask_Chain,		*,		60,		15
	BalaclavaMask_Pig,		*,		60,		15
	PaydayMask_Chains,			*,		40,		10
	PaydayMask_Dallas,				*,		40,		10
	PaydayMask_Hoxton,			*,		40,		10
	PaydayMask_Wolf,			*,		40,		10
	Headdress_Wolf,	*,		200,		20
	
	<Category> Helmets
	BallisticHelmet_Navy,	*,		300,	100
	BallisticHelmet_Winter,	*,		300,	100
	
	<Category> Caps & Hats
	BoonieHat_Winter,		*,		20,		7
	Shemag_Brown,			*,		55,		18
	Shemag_Green,			*,		55,		18
	Shemag_Red,			*,		55,		18
	Shemag_White,			*,		55,		18
	SnowstormUshanka_Brown,			*,		55,		18
	SnowstormUshanka_Navy,			*,		55,		18
	SnowstormUshanka_Olive,			*,		55,		18
	SnowstormUshanka_White,			*,		55,		18
	SherpaHat_Black,			*,		55,		18
	SherpaHat_Blue,			*,		55,		18
	SherpaHat_Red,			*,		55,		18
	BudenovkaHat_Gray,			*,		55,		18
	NBCHoodWhite,			*,		100,	30
	
	<Category> Jackets & Coats
	BushlatPoliceJacket_Blue,	*,		34,		8
	DownJacket_Blue,		*,		30,		7
	DownJacket_Green,		*,		30,		7
	DownJacket_Orange,		*,		30,		7
	DownJacket_Red	,		*,		30,		7
	NavyUniformJacket,	*,		120,	35
	OMKJacket_Navy,		*,		120,	35
	GorkaEJacket_Winter,	*,		140,	45
	NBCJacketWhite,			*,		250,	80
	
	<Category> Pants
	GorkaPants_Winter,		*,		130,	40
	NavyUniformPants,		*,		100,	30
	OMKPants_Navy,			*,		100,	30
	NBCPantsWhite,			*,		200,	65

	<Category> Medications
	ChelatingTablets,		*,		8,		5
	
	<Category> Packaged Food
	CrabCan,				*,		4,		2
	
	<Category> Drinks
	GlassBottle,			*,		5,		2
	FilteringBottle,		*,		35,		15
	
	<Category> Ghillie
	GhillieBushrag_Winter,	*,		400,	130
	GhillieHood_Winter,		*,		220,	70
	GhillieTop_Winter,	*,		600,	200
	GhillieSuit_Winter,	*,		1000,	300
	
	<Category> Vests
	HuntingVest_Winter,			*,		55,		18
	UKAssVest_Winter,			*,		100,	35
	PlateCarrierVest_Winter,		*,		250,	80
	
	<Category> Tools (big)
	Iceaxe,				*,		10,		4
	
	<Category> Tools (small)
	Jig,				*,		30,		10
	
	<Category> Shoes & Boots
	NBCBootsWhite,			*,		150,	50
	
	<Category> Pants
	NavyUniformPants,		*,		100,	30
	
	<Category> Holster & Pouches
	PlateCarrierHolster_Winter,	*,		60,		20
	PlateCarrierPouches_Winter,	*,		100,		20
	
	<Category> Meat
	RedCaviar,		S,		5,		3	
	
	<Category> Hardware Supplies
	ScientificBriefcase,	*,		2000,	100
	ScientificBriefcaseKeys,*,		2000,	100
	
	<Category> Gloves
	SkiGloves_90s,			*,		25,		6
	SkiGloves_Blue,			*,		25,		6
	SkiGloves_Red,			*,		25,		6
	
	<Category> Glasses
	SkiGoggles_BlackYellow,		*,		60,		30
	SkiGoggles_WhiteClear,		*,		60,		30
	SkiGoggles_WhiteDark,		*,		60,		30
	
	<Category> Knights Clothing
	WitchHoodCoif_Black,			*,		250,	80
	WitchHoodCoif_Brown,			*,		250,	80
	WitchHoodCoif_Red,			*,		250,	80

	REMOVE THESE FROM YOUR TRADER CONFIG, THEY PROBABLY DON'T WORK ANYMORE:
	
	Vodka,					*,		12,		8
	
	WitchHood_Chainmail_Black,			*,		250,	80
	WitchHood_Chainmail_Brown,			*,		250,	80
	WitchHood_Chainmail_Red,			*,		250,	80
		
 
Thanks, Rob.



