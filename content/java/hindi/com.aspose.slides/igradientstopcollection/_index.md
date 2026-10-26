---
title: IGradientStopCollection
second_title: Aspose.Slides for Java API संदर्भ
description: ग्रेडिएंट स्टॉप्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/igradientstopcollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

ग्रेडिएंट स्टॉप्स के संग्रह को दर्शाता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [add(float position, Color color)](#add-float-java.awt.Color-) | एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है। |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है। |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है। |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप को हटाता है। |
| [clear()](#clear--) | एक संग्रह से सभी ग्रेडिएंट स्टॉप को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**  
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.awt.Color | नए ग्रेडिएंट स्टॉप का Color। |

**वापसी मान:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का Color। |

**वापसी मान:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का Color। |

**वापसी मान:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए ग्रेडिएंट स्टॉप को सम्मिलित करने के लिए संग्रह में इंडेक्स। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.awt.Color | नए ग्रेडिएंट स्टॉप का Color। |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए ग्रेडिएंट स्टॉप को सम्मिलित करने के लिए संग्रह में इंडेक्स। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का Color। |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और निर्दिष्ट इंडेक्स पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए ग्रेडिएंट स्टॉप को सम्मिलित करने के लिए संग्रह में इंडेक्स। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का Color। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ग्रेडिएंट स्टॉप का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

एक संग्रह से सभी ग्रेडिएंट स्टॉप को हटाता है।