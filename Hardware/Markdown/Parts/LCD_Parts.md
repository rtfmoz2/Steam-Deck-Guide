# Steam Deck LCD Parts And Measurements

## [Chip ID](https://www.ifixit.com/Guide/Steam+Deck+Chip+ID/147811)

## [Offical CAD Files](https://gitlab.steamos.cloud/SteamDeck/hardware)

## Main / Motherboard
- [USB-C Connector - 12402143E512A](https://www.amphenol-cs.com/product/12402143e512a.html)

### Different Revisions
![F7A Rev E & F (1)](../../Images/LCD/Production/KenFixed_LCD_Motherboard_F7A_E_F_1.png)
![F7A Rev E & F (2)](../../Images/LCD/Production/KenFixed_LCD_Motherboard_F7A_E_F_2.png)
![F7A Rev E & F (3)](../../Images/LCD/Production/KenFixed_LCD_Motherboard_F7A_E_F_3.png)
![F7A Rev F(D) & F(A)](../../Images/LCD/Production/KenFixed_LCD_Motherboard_F7A_FD_FA_1.png)

### Panelization - [Explanation By PCBWay](https://www.pcbway.com/blog/PCB_Basic_Information/What_is_PCB_Panelization_PCB_Knowledge_eaf7e88f.html)
![Panelization](../../Images/LCD/Production/KenFixed_LCD_Motherboards_B_D_A.png)
![Panelization Explanation](../../Images/LCD/Production/Dan2wik_Panelization_Tags_Explanation.png)

### Measurements

![Kenfixed_LCD_Measurements_1](../../Images/Measurements/Kenfixed_LCD_Measurements_1.png)
![Kenfixed_LCD_Measurements_2](../../Images/Measurements/Kenfixed_LCD_Measurements_2.png)

F7A Revision Pads  
![F7A Revision Pads](../../Images/Measurements/Kenfixed_LCD_F7A_Pads.png)

The one above the APU should be roughly 2mm thick, 7.5mm wide and 11mm in length.  
Any of these measurements might not be perfect, give or take an extra 0.5mm.

### Diode Readings
![Diode Readings](../../Images/Measurements/KenFixed_LCD_OLED_Diode_Readings.png)

### Traces
![Kenfixed_LCD_Traces_1](../../Images/Traces/Kenfixed_LCD_Traces_1.png)
![Kenfixed_LCD_Traces_2](../../Images/Traces/Kenfixed_LCD_Traces_2.png)

## Parts

### Joystick
- Uses PS5 pinouts
- Thumbstick cap is capacitive (that's what the wire that's soldered to the module is for)
- There are two Types (A or B)

#### Backside Of Right Joystick
![Right Joystick Backside](../../Images/LCD/Production/Kenfixed_LCD_Joystick_Backside.png)

#### Other Controllers' Pinouts ([Source (?)](https://www.reddit.com/r/ConsoleRepairUK/comments/18i6al8/ps5_ps4_xbox_hall_effect_analog_stick_pinout/))
![Other Pinouts](../../Images/Measurements/4nH3r0_Controller_Pinouts.webp)

### Fan Header
![TE Connectivity 2483180-4](../../Images/Other/Mouser_TE_Connectivity_2483180-4.png)
- [TE Connectivity 2483180-4](https://eu.mouser.com/ProductDetail/TE-Connectivity/2483180-4?qs=sGAEpiMZZMvlX3nhDDO4ADM3qnTU%252BbjxNmfJQeot/Po%3D)
- [Source: Valve Employee (u/SteamHWFeedBack)](https://www.reddit.com/r/SteamDeck/comments/1j0k1y0/comment/mfceils/)

### USB-C Port

#### Components
- Caps: .22u, 0201, 25V Rated (USB-3/DP may not work without them)
- Diodes: PESD5V0C1BSF
- Might be able to get away with missing ESD components but it's not recommended
- [Source: Valve Employee (u/SteamHWFeedBack)](https://www.reddit.com/r/SteamDeck/comments/1j0k1y0/comment/mfc7u68/)

- Additional pictures by Ayo_Gart:

![USB-C Pinout Components 1](../../Images/Measurements/Ayo_Gart_LCD_USB-C_Components_1.png)
![USB-C Pinout Components 2](../../Images/Measurements/Ayo_Gart_LCD_USB-C_Components_2.png)

#### Pinout
![USB-C Pinout 1](../../Images/Measurements/Ayo_Gart_LCD_USB-C_Pinout_1.png)
![USB-C Pinout 2](../../Images/Measurements/Ayo_Gart_LCD_USB-C_Pinout_2.png)
![USB-C Pinout 5](../../Images/Measurements/Ayo_Gart_LCD_USB-C_Pinout_3.png)

### Additional information
- [Different input / controller daughterboard revisions might not be "drop-in" replacements (firmware flashing might be needed)](https://www.reddit.com/r/SteamDeckModded/comments/1gcftli/can_i_really_use_a_rev_f_instead_of_another_rev_g/)