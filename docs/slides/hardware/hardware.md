<!-- .slide: id="hardware-hardware" -->

# Hardware

===

<!-- .slide: class="columns layout" id="hardware-prototype" -->

## Prototype

- Column

    ![Prototype Photo](slides/hardware/prototype.jpg)

- Column

    - Experimentation started with the following hardware that I mostly already owned

===

<!-- .slide: class="columns layout" -->

### [Samsung 32" Class M5300 Full HD TV](https://www.samsung.com/us/televisions-home-theater/tvs/full-hd-tvs/32--class-m5300-full-hd-tv-un32m5300afxza/)

- Column

    - After moving homes we no longer had an obvious spot for this TV, so it was available for experimentation
    - Full HD (1920×1080) resolution
    - \$0

- Column

    ![Samsung 32" Class M5300 Full HD TV](slides/hardware/samsung-un32m5300.jpg)

===

<!-- .slide: class="columns layout" -->

### [Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)

- Column

    ![Raspberry Pi 3 Model B](slides/hardware/raspberry-pi-3.jpg)

- Column

    - Received as a prize at a work function years ago
    - Came with a power supply and heat sinks
    - Sufficient to drive the Full HD TV
    - \$0

===

<!-- .slide: class="columns layout" -->

### [Adafruit PIR Sensor](https://www.adafruit.com/product/189)

- Column

    - Passive Infrared sensor detects motion from the IR emitted from our bodies
    - Runs on 5V–12V power and the Pi provides 5V
    - Sensing range is up to 7 meters within a 120-degree cone
    - Comes with a 1-foot cable/socket
    - There are cheaper alternatives, but product reviews were poor
    - \$11

- Column

    ![Adafruit PIR Sensor](slides/hardware/adafruit-pir.png)

===

<!-- .slide: class="columns layout" -->

### [Smraza Basic Starter Kit with Breadboard](https://www.amazon.com/gp/product/B01HRR7EBG/ref=ppx_yo_dt_b_asin_title_o09_s00?ie=UTF8&psc=1)

- Column

    ![Smraza Basic Starter Kit with Breadboard](slides/hardware/smraza-starter-kit.jpg)

- Column

    - Includes the following necessities and more:
        - Breadboard,
        - Power supply
        - LEDs
        - Resistors
        - Push buttons
        - Patch wires
    - Owning this kit gives me some hacker cred!
    - \$13

===

### Wiring Diagram

![Fritzing Diagram](slides/hardware/fritzing-diagram.png) <!-- .element: style="max-height: 900px;" -->

===

<!-- .slide: id="hardware-final-design" -->

## Final Design Changes

- The 32" TV prototype display was unsatisfactory for the intended location
    - Too large for the aesthetic goals
    - Too pixelated for the viewing distance
        - Full HD (1920×1080) on a 32" display works out to 70ppi
        - For comparison, an iPhone 7 Plus display packs 401ppi
- The following hardware upgrades were used for the final design

===

<!-- .slide: class="columns layout" -->

### [Dell UltraSharp 25" QHD Monitor (U2518D)](https://www.dell.com/en-us/work/shop/dell-ultrasharp-25-monitor-u2518d/apd/210-amll/monitors-monitor-accessories)

- Column

    ![Dell UltraSharp 25" QHD Monitor (U2518D)](slides/hardware/dell-u2518d.jpg)

- Column

    - Has a 25" screen, which is about the right size for this installation
    - Employs an IPS panel with good viewing angles, even in portrait mode
    - Projects a QHD resolution (2560×1440) yielding 117ppi for crisper text and sharper images
    - Purchased used from a coworker
    - \$125

===

<!-- .slide: class="columns layout" -->

### [Raspberry Pi 4 Model B with 1GB RAM](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

- Column

    - Pi 4 is the only model capable of going above Full HD, up to 4K (3840×2160)
    - Available with 1GB, 2GB, or 4GB of RAM
    - Also purchased a power supply and inexpensive 16GB microSD
    - \$45

    ***

    - Hindsight: purchase a 2GB or 4GB Pi to avoid needing a separate swap drive (see next slide)

- Column

    ![Raspberry Pi 4 Model B with 1GB RAM](slides/hardware/raspberry-pi-4.jpg)

===

<!-- .slide: class="columns layout" -->

### 2GB USB Thumb Drive

- Column

    ![USB Thumb Drive](slides/hardware/usb-thumb-drive.jpg)

- Column

    - The prototype Pi 3 never crashed due to out of memory errors
    - Chrome would show "Aww, Snap!" errors after hours or days on the Pi 4
    - Confusingly, measurements show only ~1/4 of RAM being used typically
    - Crashes went away with more swap space
    - Advised to not use the OS MicroSD card for swap space
    - \$0

===

<!-- .slide: id="hardware-costs" -->

## Costs

===

### Prototype Costs

| Part                                                                                                                                                 | Cost |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---: |
| [Samsung 32" Class M5300 Full HD TV](https://www.samsung.com/us/televisions-home-theater/tvs/full-hd-tvs/32--class-m5300-full-hd-tv-un32m5300afxza/) |  \$0 |
| [Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)                                                               |  \$0 |
| [Adafruit PIR Sensor](https://www.adafruit.com/product/189)                                                                                          | \$11 |
| [Smraza Basic Starter Kit with Breadboard](https://www.amazon.com/gp/product/B01HRR7EBG/ref=ppx_yo_dt_b_asin_title_o09_s00?ie=UTF8&psc=1)            | \$13 |
|                                                                                                                                                      | \$24 |

===

### Final Design Costs

| Part                                                                                                                                                         |  Cost |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----: |
| [Dell UltraSharp 25" QHD Monitor (U2518D)](https://www.dell.com/en-us/work/shop/dell-ultrasharp-25-monitor-u2518d/apd/210-amll/monitors-monitor-accessories) | \$125 |
| [Raspberry Pi 4 Model B with 1GB RAM](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/) and accessories                                          |  \$45 |
| [Adafruit PIR Sensor](https://www.adafruit.com/product/189)                                                                                                  |  \$11 |
| 2GB USB Thumb Drive                                                                                                                                          |   \$0 |
|                                                                                                                                                              | \$181 |

<!-- | [Smraza Case for Rasberry Pi 4 B](https://www.amazon.com/gp/product/B07VDCT57F/ref=ppx_yo_dt_b_asin_title_o04_s01?ie=UTF8&psc=1)                     | \$10 | -->

===

### Costs Compared to Off-the-Shelf DAKboard

TODO: Cost comparison