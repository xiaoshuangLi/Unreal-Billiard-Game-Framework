# Create Billiard Game

### Create Blueprint Project
```Blueprint``` is necessary.Then add ```BilliardGameFramework``` to the project you create.

![Blueprint Project](https://github.com/xiaoshuangLi/Unreal-Documation/raw/master/BilliardGameFramework/CreateBilliardGame/imgs/CreateBlueprintGame.png)

### Create Empty Level
Select and create, i use name ```World```.

![Empty Level](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/CreateEmptyLevel.png)

### Create Game Actor from ```BP_Game```

Right click in your content browser, and click ```Blueprint Class``` in the popup to create a new blueprint.You’ll see a popup like this, you’ll want to hit the ```All Classes``` dropdown, and type ```BP_Game``` in the input field that appears.Select and create, i use name ```BP_BilliardGame```.

![Game Actor](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/CreateGameBlueprint.png)

### Add ```BP_BilliardGame``` to ```World``` Level

Just drag and drop in.

![BP_BilliardGame in World](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/AddGameActor.png)

### Open ```World``` Level Blueprint

All the following blueprints, you can just copy from level blueprint ```BilliardGameFramework/Maps/World```.

![World Level Blueprint](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/OpenLevelBlueprint.png)

### Create ```GetGame``` Function

```GetGame``` return the ```BP_BilliardGame``` actor, it's convenient for later program.

![GetGame](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/CreateFunctionGetGame.png)

### Add input to Play

For this demo, we use Left-Mouse click to control.When players released fire ```StopAim``` the white ball will been shot out.

![Left-click Input](https://github.com/xiaoshuangLi/Unreal-Documation/blob/master/BilliardGameFramework/CreateBilliardGame/imgs/CreateInputEvent.png)

### Finally

Now you've done all the programming.Just hit ```Play``` and left click in the viewport.You'll see the game you just created.

Should look like this: https://youtu.be/SuIkp_kTRRQ
