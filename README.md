# 🎸 ChordCrack Guitar Chord Samples

<div align="center">
  
  **High-Quality Guitar Chord Audio Library for Education & Development**
  
  [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
  [![Audio Format](https://img.shields.io/badge/Format-M4A%20%7C%20WAV-blue.svg)](https://github.com/mmaaseide23/ChordCrack_Assets)
  [![Quality](https://img.shields.io/badge/Quality-Studio-green.svg)](https://github.com/mmaaseide23/ChordCrack_Assets)
  
</div>

## 📖 About

This repository contains professionally recorded guitar chord audio samples created for the **ChordCrack** ear training application. These high-quality samples are now available for the community to use in educational projects, music applications, and development work.

## 🎵 Sample Collection

### Basic Chords
- **Major Chords**: A, B, C, D, E, F, G
- **Minor Chords**: Am, Bm, Cm, Dm, Em, Fm, Gm

### Advanced Chords
- **Power Chords**: E5, A5, D5, G5, C5, F5, B5, F#5, C#5, G#5, D#5, A#5
- **Barre Chords**: Full barre variations of major and minor chords
- **7th Chords**: Dominant 7th, Minor 7th, Major 7th variations
- **Individual Strings**: Separate recordings for progressive learning

### Audio Specifications
- **Format**: M4A (optimized for mobile) / WAV (high quality)
- **Sample Rate**: 44.1 kHz
- **Bit Depth**: 16-bit
- **Recording**: Clean DI guitar signal, professionally mixed
- **Duration**: 2-4 seconds per sample
- **File Naming**: Consistent naming convention for easy integration

## 🚀 Usage Examples

### iOS/Swift Development
```swift
// Load chord samples in your iOS app
let chordURL = Bundle.main.url(forResource: "C_major", withExtension: "m4a")
let audioPlayer = try AVAudioPlayer(contentsOf: chordURL!)
audioPlayer.play()
```

### Web Development
```javascript
// HTML5 Audio integration
const audio = new Audio('C_major.m4a');
audio.play();
```

### Unity Game Development
```csharp
// Unity AudioSource integration
AudioSource audioSource = GetComponent<AudioSource>();
AudioClip chordClip = Resources.Load<AudioClip>("C_major");
audioSource.clip = chordClip;
audioSource.Play();
```

## 📋 File Structure

```
ChordCrack_Assets/
├── basic-chords/
│   ├── C_major.m4a
│   ├── D_major.m4a
│   └── ...
├── power-chords/
│   ├── E5.m4a
│   ├── A5.m4a
│   └── ...
├── individual-strings/
│   ├── E2_fret0.m4a
│   ├── A3_fret2.m4a
│   └── ...
└── README.md
```

## 📄 License

This work is licensed under the **Creative Commons Attribution 4.0 International License** (CC BY 4.0).

### You can:
- ✅ Use in commercial and non-commercial projects
- ✅ Modify, remix, and transform the samples
- ✅ Distribute and share the samples
- ✅ Include in music education apps
- ✅ Use in game development
- ✅ Incorporate into music production

### You must:
- 📝 Provide attribution to Michael Maaseide / ChordCrack
- 🔗 Include a link to this repository
- 📋 Indicate if you made changes to the samples

## 🏷️ Attribution Examples

### For Apps/Software
```
Guitar chord samples provided by ChordCrack
Created by Michael Maaseide
Licensed under CC BY 4.0
Source: https://github.com/mmaaseide23/ChordCrack_Assets
```

### For Academic/Educational Use
```
Maaseide, M. (2025). ChordCrack Guitar Chord Sample Library. 
Retrieved from https://github.com/mmaaseide23/ChordCrack_Assets
Licensed under Creative Commons Attribution 4.0 International
```

### For Music Production
```
Guitar chord samples by Michael Maaseide (ChordCrack)
Licensed under CC BY 4.0
```

## 🎯 Use Cases

- **Music Education Apps**: Integrate chord samples for ear training
- **Game Development**: Add realistic guitar sounds to games  
- **Music Production**: Use as MIDI trigger samples or backing tracks
- **Web Applications**: Enhance music theory learning tools
- **Research Projects**: Academic studies in music cognition and learning
- **Prototyping**: Quick audio assets for development and testing

## 🤝 Contributing

Found an issue with the samples or have suggestions for improvements?

1. **Report Issues**: Use the GitHub issue tracker
2. **Sample Requests**: Suggest additional chords or variations
3. **Quality Improvements**: Report audio quality concerns

## 🔗 Related Projects

- **[ChordCrack App](https://github.com/mmaaseide23/ChordCrack)** - The main application using these samples
- **[ChordCrack Legal](https://github.com/mmaaseide23/ChordCrack-Legal)** - Privacy policy and terms

## 📞 Contact

**Michael Maaseide**
- Email: chordcrackhelp@gmail.com
- GitHub: [@mmaaseide23](https://github.com/mmaaseide23)

## 📊 Usage Stats

If you use these samples in your project, we'd love to hear about it! Feel free to reach out and let us know how you're using the ChordCrack sample library.

---

**Made with ❤️ for the music education community**

*These samples were created as part of the ChordCrack project to help guitarists worldwide develop their ear training skills.*
