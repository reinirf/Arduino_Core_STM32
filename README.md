# Arduino core support for STM32 based boards
[![GitHub release](https://img.shields.io/github/release/stm32duino/Arduino_Core_STM32.svg)](https://github.com/stm32duino/Arduino_Core_STM32/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/stm32duino/Arduino_Core_STM32/1.5.0.svg)](https://github.com/stm32duino/Arduino_Core_STM32/compare/1.5.0...master)
[![Build Status](https://travis-ci.com/reinirf/Arduino_Core_STM32.svg?branch=master)](https://travis-ci.com/reinirf/Arduino_Core_STM32)

* [Introduction](https://github.com/stm32duino/Arduino_Core_STM32#Introduction)<br>
* [Getting Started](https://github.com/stm32duino/Arduino_Core_STM32#getting-started)<br>
* [Boards available](https://github.com/stm32duino/Arduino_Core_STM32#boards-available)<br>
* [Troubleshooting](https://github.com/stm32duino/Arduino_Core_STM32#troubleshooting)<br>
* [Wiki](https://github.com/stm32duino/wiki/wiki/)

## Introduction

This repo adds the support of STM32 MCU in Arduino IDE.<br>

This porting is based on:
* [STM32Cube MCU Packages](https://www.st.com/en/embedded-software/stm32cube-mcu-packages.html) including:
    * The HAL hardware abstraction layer, enabling portability between different STM32 devices via standardized API calls
    * The Low-Layer (LL) APIs, a light-weight, optimized, expert oriented set of APIs designed for both performance and runtime efficiency
    * CMSIS device defintion for STM32
* [CMSIS](https://developer.arm.com/embedded/cmsis): Cortex Microcontroller Software Interface Standard (CMSIS) is a vendor-independent hardware abstraction layer for the Cortex®-M processor series and defines generic tool interfaces. It has been packaged as a module for Arduino IDE: https://github.com/stm32duino/ArduinoModule-CMSIS
* [GNU Arm Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm): Arm Embedded GCC compiler, libraries and other GNU tools necessary for bare-metal software development on devices based on the Arm Cortex-M. Packages are provided thanks: https://github.com/stm32duino/arm-none-eabi-gcc


## Getting Started

This repo is available as a package usable with [Arduino Boards Manager](https://www.arduino.cc/en/guide/cores).

Use this link in the "*Additional Boards Managers URLs*" field:

https://github.com/stm32duino/BoardManagerFiles/raw/master/STM32/package_stm_index.json


For full instructions on using the "**Boards Manager**", see the [Getting Started](https://github.com/stm32duino/wiki/wiki/Getting-Started) page.

Advanced user can use the repository to benefit from the latest development. See the [Using git repository](https://github.com/stm32duino/wiki/wiki/Using-git-repository) page.

User can add a STM32 based board following this [wiki](https://github.com/stm32duino/wiki/wiki/Add-a-new-variant-(board)).

## Boards available

| Status | [Nucleo 144](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-eval-tools/stm32-mcu-eval-tools/stm32-nucleo-boards.html) | Release | Comment |
| :---: | --- | :---: | :--- |
| :green_heart: | [Nucleo H743ZI](https://www.st.com/en/evaluation-tools/nucleo-h743zi.html) | *1.5.0* |  |

## Next release

  See [milestones](https://github.com/stm32duino/Arduino_Core_STM32/milestones) to have an overview of the next release content.

## Troubleshooting

### Important notice:
Previously, support was performed on [stm32duino forum](http://stm32duino.com). This forum, will be be read only from **Saturday 27th April**. User registration is no more possible. Further information [here](http://stm32duino.com/viewtopic.php?f=16&t=4540).

If you have any issue, you could [file an issue on Github](https://github.com/stm32duino/Arduino_Core_STM32/issues/new).

If you already have an account on [stm32duino forum](http://stm32duino.com), you can always submit a topic on the [stm32duino forum](http://stm32duino.com) until the _Saturday 27th April_:

 * questions on the [STM32 Core](http://stm32duino.com/viewforum.php?f=48)
 
 * bugs/enhancements on the [STM core: Bugs and enhancements](http://stm32duino.com/viewforum.php?f=49)

In any case, it always fine to search on those topics before submit an issue.
**We are currently working on finding the best handover solution.**
