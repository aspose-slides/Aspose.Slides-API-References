---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Java API संदर्भ
description: डुओटोन प्रभाव का प्रतिनिधित्व करने वाली अपरिवर्तनीय वस्तु।
type: docs
url: /hi/com.aspose.slides/iduotoneeffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय वस्तु जो डुओटोन प्रभाव का प्रतिनिधित्व करती है। प्रत्येक पिक्सेल के लिए, clr1 और clr2 को रैखिक इंटरपोलेशन के माध्यम से मिलाकर उस पिक्सेल के लिए नया रंग निर्धारित करती है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColor1()](#getColor1--) | डार्क पिक्सेल्स के लिए लक्ष्य रंग प्रारूप लौटाता है। |
| [getColor2()](#getColor2--) | लाइट पिक्सेल्स के लिए लक्ष्य रंग प्रारूप लौटाता है। |

### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

डार्क पिक्सेल्स के लिए लक्ष्य रंग प्रारूप लौटाता है। केवल-पढ़ने योग्य java.awt.Color।

**रिटर्न:**
java.awt.Color

### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

लाइट पिक्सेल्स के लिए लक्ष्य रंग प्रारूप लौटाता है। केवल-पढ़ने योग्य java.awt.Color।

**रिटर्न:**
java.awt.Color