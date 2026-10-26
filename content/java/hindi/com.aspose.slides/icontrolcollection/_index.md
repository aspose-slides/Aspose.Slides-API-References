---
title: IControlCollection
second_title: Aspose.Slides के लिये Java API संदर्भ
description: ActiveX नियंत्रणों का संग्रह।
type: docs
url: /hi/com.aspose.slides/icontrolcollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX नियंत्रकों का संग्रह।

## विधियां

| विधि | विवरण |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | संग्रह से एक ActiveX नियंत्रण हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह से निर्दिष्ट स्थिति पर संग्रहीत एक ActiveX नियंत्रण हटाता है। |
| [clear()](#clear--) | संग्रह से सभी नियंत्रण हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर एक नियंत्रण लौटाता है। |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | संग्रह में एक नया नियंत्रण बनाता और जोड़ता है। |

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

संग्रह से एक ActiveX नियंत्रण हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | हटाने के लिए एक नियंत्रण। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह से निर्दिष्ट स्थिति पर संग्रहीत एक ActiveX नियंत्रण हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए नियंत्रण का अनुक्रमणिका। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी नियंत्रण हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

निर्दिष्ट स्थिति पर एक नियंत्रण लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | नियंत्रण का अनुक्रमणिका। |

**वापसी:**
[IControl](../../com.aspose.slides/icontrol)

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

संग्रह में एक नया नियंत्रण बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| controlType | int | जोड़ने के लिए नियंत्रण का प्रकार। |
| x | float | आकार के फ्रेम के बाएँ पक्ष के लिए X-निर्देशांक। |
| y | float | आकार के फ्रेम के शीर्ष पक्ष के लिए Y-निर्देशांक। |
| width | float | आकार के फ्रेम की चौड़ाई। |
| height | float | आकार के फ्रेम की ऊँचाई। |

**वापसी:**
[IControl](../../com.aspose.slides/icontrol) - बनाया गया नियंत्रण [IControl](../../com.aspose.slides/icontrol)।