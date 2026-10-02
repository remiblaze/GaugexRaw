# Gaugex Raw: Streaming Loudness Meter

![Gaugex Raw free one-knob streaming loudness meter UI](https://raw.githubusercontent.com/RemiBlaze/GaugexRaw/main/gaugexraw-ui-screenshot.png)

**Hit your streaming loudness target with confidence.**

Gaugex Raw is a dead-simple LUFS meter: pick your streaming target, then watch a big integrated-LUFS readout with a green/amber/red on-target light. It measures only. Your audio passes through completely unchanged, bit-transparent with zero added latency.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/GaugexRaw/releases/latest) and pick your platform.

**macOS**
1. Download **`GaugexRaw_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. Gaugex Raw appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`GaugexRaw_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. Gaugex Raw appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 📊 What It Measures

Gaugex Raw is a loudness meter built on the **ITU-R BS.1770-4 / EBU R128** standard.

- **Integrated LUFS**: the big, central readout: your overall program loudness, measured with proper BS.1770-4 gating (−70 LUFS absolute gate, −10 LU relative gate).
- **Momentary LUFS**: 400 ms sliding-window loudness.
- **Short-Term LUFS**: 3-second sliding-window loudness.
- **True Peak (dBTP)**: inter-sample peak, measured with 4× oversampling to catch peaks that a normal sample meter misses.

### Streaming Targets
Pick where your track is headed and the on-target light tells you if you're there:

- **Spotify**: −14 LUFS
- **YouTube**: −14 LUFS
- **Apple Music**: −16 LUFS
- **Club**: −6 LUFS
- **Custom**: dial in any target from −24 to −6 LUFS

The **on-target light** reads green when you're within 1 LU of target, amber within 3 LU, and red beyond that, with a live delta showing exactly how far off you are. The **Fire Head** rides the loudness as a living needle, a dim ember under target, a calm glow on target, a white-hot flicker when you're too loud.

### Measure Only: Nothing Added
Gaugex Raw does not process, shape, or colour your sound. The signal passes through **bit-transparent**, and it reports **zero latency** to the host, so you can leave it inserted anywhere in your chain without affecting playback or timing. A **Reset** button clears the integrated measurement so you can start a fresh reading.

No factory presets: the streaming target selector is all you need.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/GaugexRaw/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/gaugex-raw/](https://remiblaze.com/plugins/gaugex-raw/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

Spotify, Apple Music, and YouTube are trademarks of their respective owners; Gaugex Raw is not affiliated with or endorsed by them. Platform names denote loudness targets only.

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
