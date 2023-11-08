# DragonFruit
Dragon Fruit, sponsored by [PCBWay](https://www.pcbway.com), a heavily modifed from AriaMelon's column staggered [Honey Dew](https://github.com/Ariamelon/Honeydew) powered by integrated RP2040 and Ariamelon's [Kiwano](https://github.com/Ariamelon/Kiwano) module.

# The DragonFruit is featured on https://kbd.news/DragonFruit-2178.html

This project is sponsored and made possible by:
![PCBWay](https://github.com/protieusz/DragonFruit/assets/118025702/c41f5eb2-1fd3-4f8a-9159-31855fbcfc03)
Your one stop solution for PCB printing / PCBA service.  Top notch customer service. Their sales department are able to do a quick test after PCBA by plugging into the PC to see if the RP2040 storage containers popped up.
Best of all, all 5 PCBs assembled are all working and top notch soldering.  Their red silkscreen really pops out and matched with their yellow font silkscreen looks really nice. Thank you PCBWay!

## VIK Certification

This DragonFruit keyboard is VIK certified per Sadek of Fingerpunch's [VIK standard](https://github.com/sadekbaroudi/vik#keyboard-sample-cards). Read more about what VIK standard does to the custom keyboard with custom pointing devices like trackballs, trackpads,etc in Sadek's VIK standard in his [GitHub](https://github.com/sadekbaroudi/vik#keyboard-sample-cards).
| Category                 | Classification          | Response           |
| -----------------------  | ----------------------- | ------------------ |
| FPC connector            | Required                | :heavy_check_mark: |
| Breakout pins            | Recommended             | :x:                |
| Supplies: SPI            | Strongly recommended    | :heavy_check_mark: |
| Supplies: I2C            | Strongly recommended    | :heavy_check_mark: |
| I2C on main PCB          | Discouraged             | no                 |
| I2C pull ups             | Informative             | N/A                |
| Supplies: RGB            | Strongly recommended    | :heavy_check_mark: |
| Supplies: Extra GPIO 1   | Required                | Digital only       |
| Supplies: Extra GPIO 2   | Required                | Digital only       |

PCB print plus assembly has been tested and working correctly.  However please print at your own risk and no support will be given.  As for the Kiwano module, please go to AriaMelon's GITHUB to get the pcb printed and assembled.  The trackball 3DP files are all located in her GITHUB.  You would need the [specific](https://github.com/Ariamelon/Kiwano/tree/main/3DP) ones for this build and they are:

| Trackball 3DP Parts              | 
| ---------------------------------| 
| Trackball Mount Low Profile.step |                           
| Knob Ribbed.step                 |                      
| Knob Base.step                   |                                          

Only the gerber files of the DragonFruit will be uploaded to this GitHub. THe PCB design was done in EasyEDA so converting to KiCad pcb file format is a pain.  Case step file will also be uploaded and the pcb anchors for the case needs a 1mm offset since I forgot to adjust it so in order to fix it, I had to melt some of the plastic off in order to be able to slide the pcb into the case. I will not update the case file anymore. Please do so at your own risk. No support will be given.

QMK code is borrowed from Aki27's [Bally](https://github.com/aki27kbd/vial-qmk/tree/vial/keyboards/aki27/bally) is working very smoothly.  I also uploaded my compiled QMK firmware. Trackball QMK code requires the QMK version above 0.19 in order to successful compiled. No support will be given for the code. Please ask the original designer/owner for support since I only copied and pasted the QMK code.

## Update: Nov 7, 2023. Final Product.

![IMG_0301](https://github.com/protieusz/DragonFruit/assets/118025702/1bbba0b1-df73-4067-8b93-f1636ab4fe97)
![IMG_0300](https://github.com/protieusz/DragonFruit/assets/118025702/513c643b-0166-4be9-9b51-d72a6865a979)
![IMG_0296](https://github.com/protieusz/DragonFruit/assets/118025702/279e61cd-fd22-428c-8a89-4d50f84bfa61)
![IMG_0295](https://github.com/protieusz/DragonFruit/assets/118025702/9b560cd7-954a-4229-a3a8-db8389f728a0)
![85B45748A8880E51D3D014F1AD25B3F6](https://github.com/protieusz/DragonFruit/assets/118025702/7c458fe6-e884-476a-9ae6-611672b9473e)
![IMG_0283](https://github.com/protieusz/DragonFruit/assets/118025702/c18913d8-602b-4464-a473-c2a37da42fd0)
![IMG_0292](https://github.com/protieusz/DragonFruit/assets/118025702/8e082802-f103-4991-808d-87574731495b)
![IMG_0290](https://github.com/protieusz/DragonFruit/assets/118025702/aeb79f02-9a28-45f8-9e96-269a30bc139b)
![IMG_0288](https://github.com/protieusz/DragonFruit/assets/118025702/12117bcf-3c85-47a3-a4af-7ac9431f85d7)
![IMG_0281](https://github.com/protieusz/DragonFruit/assets/118025702/7405078b-7db9-41d0-a9a5-f53f3984db03)
![IMG_0282](https://github.com/protieusz/DragonFruit/assets/118025702/ff493651-3c46-4aca-9a65-ab8e3bd607ca)

No PCB, fit test.

![IMG_0180](https://github.com/protieusz/DragonFruit/assets/118025702/b944affd-a064-4418-bfdc-413b9a10dbe0)
![IMG_0163](https://github.com/protieusz/DragonFruit/assets/118025702/e65c0252-874a-43cc-b0ef-f4e6b6d8387e)


Fusion360

![Screenshot 2023-10-03 at 12 02 02 AM](https://github.com/protieusz/DragonFruit/assets/118025702/51171fbe-779d-48e9-805a-6abb9b44eff7)
![Screenshot 2023-10-03 at 12 02 12 AM](https://github.com/protieusz/DragonFruit/assets/118025702/361b1a8d-a1b9-464d-822e-5cb9fcad9cdb)
![Screenshot 2023-09-26 at 10 12 14 AM](https://github.com/protieusz/DragonFruit/assets/118025702/c082feda-920d-43b1-b5e3-88322786de66)
![Screenshot 2023-09-26 at 10 12 30 AM](https://github.com/protieusz/DragonFruit/assets/118025702/869e89ac-0210-40f2-a872-42a6cba61591)
![Screenshot 2023-09-26 at 10 13 27 AM](https://github.com/protieusz/DragonFruit/assets/118025702/c0bfc46f-618e-4536-b828-01d930502527)

Printed Case

![IMG_0090](https://github.com/protieusz/DragonFruit/assets/118025702/6edc8c81-3efc-4e97-aa05-8ddde992c0af)
![IMG_0091](https://github.com/protieusz/DragonFruit/assets/118025702/ee471290-4030-4d49-b313-78180ed9bb3d)

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

DragonFruit by ProtieusKeebs is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)
