---
title: IControlCollection
second_title: Aspose.Slides for Android द्वारा Java API रेफ़रेंस
description: ActiveX कंट्रोल्स का संग्रह।
type: docs
url: /hi/com.aspose.slides/icontrolcollection/
---
**सभी लागू इंटरफेस:**  
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX कंट्रोल्स का संग्रह।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | कलेक्शन से एक ActiveX कंट्रोल को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन में निर्दिष्ट स्थिति पर स्थित एक ActiveX कंट्रोल को हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी कंट्रोल्स को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर एक कंट्रोल लौटाता है। |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | कलेक्शन में एक नया कंट्रोल बनाता और जोड़ता है। |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

कलेक्शन से एक ActiveX कंट्रोल को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | हटाने के लिए एक कंट्रोल। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

कलेक्शन में निर्दिष्ट स्थिति पर स्थित एक ActiveX कंट्रोल को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए कंट्रोल का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

कलेक्शन से सभी कंट्रोल्स को हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

निर्दिष्ट स्थिति पर एक कंट्रोल लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कंट्रोल का इंडेक्स। |

**वापसी मान:**  
[IControl](../../com.aspose.slides/icontrol)

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

कलेक्शन में एक नया कंट्रोल बनाता और जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| controlType | int | जोड़ने के लिए कंट्रोल का प्रकार। |
| x | float | शेप के फ्रेम के बायाँ पक्ष के लिए X-निर्देशांक। |
| y | float | शेप के फ्रेम के शीर्ष पक्ष के लिए Y-निर्देशांक। |
| width | float | शेप के फ्रेम की चौड़ाई। |
| height | float | शेप के फ्रेम की ऊँचाई। |

**वापसी मान:**  
[IControl](../../com.aspose.slides/icontrol) - निर्मित कंट्रोल [IControl](../../com.aspose.slides/icontrol)।