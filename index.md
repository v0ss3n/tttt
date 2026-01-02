---
title: /tttt
layout: home
permalink: /
---

# t-t-t-t

*textile touch to tones*

The *textile touch to tones* is a capacitive touch keyboard that has been developed by Michelle Vossen to easily turn electronic textiles into Bluetooth MIDI interfaces. 

![]({{ site.baseurl }}/assets/images/tttt.jpg) 

With the t-t-t-t, you can turn e-textiles into wireless keyboards. Scroll down to see some possibilities! 

**To learn more about e-textiles, go to the [e-textiles tab](/e-textiles.html).**

## Getting started
So how do you turn electronic textiles into MIDI keyboards? To get started, you need the t-t-t-t, a USB-C power supply (5V), and 8-10 alligator clip cables (or conductive thread or tape). 

1. **Attach your e-textiles to the t-t-t-t.** The easiest way to do this is by clipping a textile with an alligator clip cable to a touch pad. You can use one e-textile sensor per touch pad. 
2. **Power the t-t-t-t via the USB-C port.** You can power it with any USB power adapter rated at 5 Volts or via your computer's USB ports. A USB-C laptop charger also works. 
3. **Connect to the t-t-t-t via the app of your choice.** This can be Garageband on an Apple device, or Synprez FM on an Android device. There are also other apps out there that support Bluetooth MIDI controllers, so feel free to explore further! If you scroll down this page a bit further, you can find instructions on how to connect to each device.
4. **Start playing!** You should hear notes play when you touch your e-textiles.

## How does it work
- With the 8 touch pads at the bottom, you can play MIDI notes. MIDI is a universal communication protocol for musical instruments. We can send these MIDI notes over Bluetooth to phone and computer apps like Garageband, Ableton and more. The 1st and the 8th note are the same note, an octave apart.
- With the 2 oct touch pads on the sides, you can move through the keyboard from octave to octave. To the left is lower, to the right is higher. When the notes don't change anymore, you've reached the limit of the keyboard.
- With the keynote button you can change the keynote you start with. The initial note is C, and each time you click you go up a note until you're back at the initial C.
- With the major/minor scale button you can toggle between major and minor scale (natural minor). This changes some of the notes from 'optimistic' to 'melancholic'. 

## Tips
Some tips for connecting textile sensors:
- If you're connecting multiple sensors, make sure the conductive parts of the connections don't touch each other. You won't break the t-t-t-t, but it will either keep making sound, or not make sound at all on those pads. This is because the touch pads are capacitive touch, and connecting them to each other makes them react to each other 
- The longer the wire between the t-t-t-t and the sensor, the harder it is for the t-t-t-t to detect touch. Keep the wires under 50 cm long if possible.

---

Some power and safety notes:

### Power
- The t-t-t-t is powered via USB-C and requires 5V. When plugging in the t-t-t-t, check the rating of the adapter that you're using - don't power it with anything higher than 5V. Any regular USB power adapter for your phone or tablet should work - but check what is written on the adapter beforehand to be sure. You can also power it from your computer USB port. Any power adapter rated at a minimum of 0,5 Ampère should fine (more is always okay with Ampère)
- You can also power the t-t-t-t via a powerbank, but in my experience not all powerbanks work well; cheap/old ones may give unstable results. 
- There are 10 conductive, touch sensitive pads on the t-t-t-t. If you place the device on a conductive area (like metal), it will not work. It will also not work if you connect the pads to each other. 1 sensor per pad!

### Safety
- Do not immerse in water (it's not a modern phone) (although theoretically you can connect one of the touch inputs to water via a wire if you want)
- Do not lick or eat (just in case that wasn't clear)

---

## How to connect to phone apps
Make sure your t-t-t-t is powered. It has a little red light that turns on when it's on. Each t-t-t-t has a unique name, so look for that when connecting :-)

### Garageband (iOS)
1. Download Garageband
2. Open Garageband, and go to an instrument if it doesn't automatically. Click on the gears in the top right corner.

    ![]({{ site.baseurl }}/assets/images/garageband.png) 

3. In settings, scroll down until you see 'Advanced'. Click on it.

    ![]({{ site.baseurl }}/assets/images/garageband1.png) 

4. Click on 'Bluetooth MIDI Devices'.

    ![]({{ site.baseurl }}/assets/images/garageband2.png) 

5. If you get this pop-up, click on Settings (usually only the first time)

    ![]({{ site.baseurl }}/assets/images/garageband3.png)

6. Click 'Allow New Connections'

    ![]({{ site.baseurl }}/assets/images/garageband4.png) 

7. Go back to Garageband and select your t-t-t-t!

    ![]({{ site.baseurl }}/assets/images/garageband5.png) 
    ![]({{ site.baseurl }}/assets/images/garageband6.png)

### Animoog Z (iOS)
1. Click on the gears in the top right corner

    ![]({{ site.baseurl }}/assets/images/animoogz.png) 

2. Click on the MIDI tab on the left

    ![]({{ site.baseurl }}/assets/images/animoogz2.png) 

3. Click on BT Connect and select your t-t-t-t

    ![]({{ site.baseurl }}/assets/images/animoogz3.png) 

### Synprez FM (Android)
1. Download MIDI BLE Connect & SynprezFM II
2. Open MIDI BLE Connect and click Start Bluetooth Scan
    
    ![]({{ site.baseurl }}/assets/images/midibleconnect1.png) 

3. Select your t-t-t-t. If it asks you to allow for connections, say yes

    ![]({{ site.baseurl }}/assets/images/midibleconnect2.png) 

4. Now you're connected to your t-t-t-t :-)

    ![]({{ site.baseurl }}/assets/images/midibleconnect3.png) 

5. Open SynprezFM II. It should be automatically connected now!

    ![]({{ site.baseurl }}/assets/images/synprez.png) 

---

## How to connect to computers 
You can send MIDI wirelessly to applications like Ableton or to browser-based apps like [https://midi.city/](midi.city) (works best on Chrome/Safari). Follow the steps below to connect!

In any case, first make sure Bluetooth is turned on on your computer.

### Steps (Windows)
1. Install [LoopMIDI](https://www.tobias-erichsen.de/software/loopmidi.html). This software is used to connect the BLE device to a virtual port, so that (web) apps on your computer can easily recognize it as a MIDI keyboard. Click on the + to add a new MIDI port.

    ![]({{ site.baseurl }}/assets/images/loopmidi.png)

2. Install [BLE-MIDI Connect](https://apps.microsoft.com/detail/9nvmlzttwwvl). You can download the free trial - it has no restrictions or end date (but if you will use it a lot, you can buy it, since it's only the price of a cup of coffee and the developers deserve coffee). This software is used to connect to your t-t-t-t. You need to log in with a Microsoft account to download it.

    ![]({{ site.baseurl }}/assets/images/blemidiconnect.png) 


### Steps (Mac)
1. Navigate to the [Audio MIDI Setup](https://support.apple.com/guide/audio-midi-setup/set-up-bluetooth-midi-devices-ams33f013765/mac) on your Mac (this is pre-installed).
2. In the Audio MIDI Setup app on your Mac, choose Window > Show MIDI Studio.
3. In the MIDI Studio window, click the Configure Bluetooth button in the toolbar.
4. Select the t-t-t-t in the list of devices, then click Connect.

### Next steps
Now you can go to Garageband, [midi.city](https://midi.city/) or other web-based MIDI keyboards that allow external keyboards to be connected and control it with the t-t-t-t! 

![]({{ site.baseurl }}/assets/images/midicity.png) 

This also works with Ableton. In Ableton select your MIDI device (loopMIDI port) here:

![]({{ site.baseurl }}/assets/images/ableton.png) 





<!-- ### Major scales (via <https://piano-music-theory.com/2016/05/31/major-scales/>)
- C Major Scale: C – D – E – F – G – A – B – C
- C Sharp Major Scale: C♯ – D♯ – E♯ – F♯ – G♯ – A♯ – B♯ – C♯ (equals the D Flat Major Scale: D♭ – E♭ – F – G♭ – A♭ – B♭ – C – D♭)
- D Major Scale: D – E – F♯ – G – A – B – C♯ – D
- E Flat Major Scale: E♭ – F – G – A♭ – B♭ – C – D – E♭
- E Major Scale: E – F♯ – G♯ – A – B – C♯ – D♯ – E
- F Major Scale: F – G – A – B♭ – C – D – E – F
- F Sharp Major Scale: F♯ – G♯ – A♯ – B – C♯ – D♯ – E♯ – F♯ (equals the G Flat Major Scale: G♭ – A♭ – B♭ – C♭ – D♭ – E♭ – F – G♭)
- G Major Scale: G – A – B – C – D – E – F♯ – G
- A Flat Major Scale: A♭ – B♭ – C – D♭ – E♭ – F – G – A♭
- A Major Scale: A – B – C♯ – D – E – F♯ – G♯ – A
- B Flat Major Scale: B♭ – C – D – E♭ – F – G – A – B♭
- B Major Scale: B – C♯ – D♯ – E – F♯ – G♯ – A♯ – B (equals the C Flat Major Scale: C♭ – D♭ – E♭ – F♭ – G♭ – A♭ – B♭ – C♭) -->

<!-- [ C , D , E , F , G , A , B , C ]
[ C♯ , D♯ , E♯ , F♯ , G♯ , A♯ , B♯ , C♯ ]
[ D♭ , E♭ , F , G♭ , A♭ , B♭ , C , D♭ ]
[ D , E , F♯ , G , A , B , C♯ , D ]
[ E♭ , F , G , A♭ , B♭ , C , D , E♭ ]
[ E , F♯ , G♯ , A , B , C♯ , D♯ , E ]
[ F , G , A , B♭ , C , D , E , F ]
[ F♯ , G♯ , A♯ , B , C♯ , D♯ , E♯ , F♯ ]
[ G♭ , A♭ , B♭ , C♭ , D♭ , E♭ , F , G♭ ]
[ G , A , B , C , D , E , F♯ , G ]
[ A♭ , B♭ , C , D♭ , E♭ , F , G , A♭ ]
[ A , B , C♯ , D , E , F♯ , G♯ , A ]
[ B♭ , C , D , E♭ , F , G , A , B♭ ]
[ B , C♯ , D♯ , E , F♯ , G♯ , A♯ , B ]
[ C♭ , D♭ , E♭ , F♭ , G♭ , A♭ , B♭ , C♭ ]

[ 60 , 62 , 64 , 65 , 67 , 69 , 71 , 72 ]
[ 61 , 63 , 65 , 66 , 68 , 70 , 72 , 73 ]
[ 61 , 63 , 65 , 66 , 68 , 70 , 72 , 73 ]
[ 62 , 64 , 66 , 67 , 69 , 71 , 73 , 74 ]
[ 63 , 65 , 67 , 68 , 70 , 72 , 74 , 75 ]
[ 64 , 66 , 68 , 69 , 71 , 73 , 75 , 76 ]
[ 65 , 67 , 69 , 70 , 72 , 74 , 76 , 77 ]
[ 66 , 68 , 70 , 71 , 73 , 75 , 77 , 78 ]
[ 66 , 68 , 70 , 71 , 73 , 75 , 77 , 78 ]
[ 67 , 69 , 71 , 72 , 74 , 76 , 78 , 79 ]
[ 68 , 70 , 72 , 73 , 75 , 77 , 79 , 80 ]
[ 69 , 71 , 73 , 74 , 76 , 78 , 80 , 81 ]
[ 70 , 72 , 74 , 75 , 77 , 79 , 81 , 82 ]
[ 71 , 73 , 75 , 76 , 78 , 80 , 82 , 83 ]
[ 71 , 73 , 75 , 76 , 78 , 80 , 82 , 83 ] -->
