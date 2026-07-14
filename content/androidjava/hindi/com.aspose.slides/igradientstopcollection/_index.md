---
title: IGradientStopCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: ग्रेडिएंट स्टॉप्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/igradientstopcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

ग्रेडिएंट स्टॉप्स के एक संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी ग्रेडिएंट स्टॉप हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.lang.Integer | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का इंडेक्स।
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का इंडेक्स।
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का इंडेक्स।
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.lang.Integer | नए ग्रेडिएंट स्टॉप का रंग। |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | उस ग्रेडिएंट स्टॉप का इंडेक्स जिसे हटाया जाना है। |

### clear() {#clear--}
```
public abstract void clear()
```


संग्रह से सभी ग्रेडिएंट स्टॉप हटाता है।