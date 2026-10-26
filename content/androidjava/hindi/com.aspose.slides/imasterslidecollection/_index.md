---
title: IMasterSlideCollection
second_title: Android के लिए Aspose.Slides, Java API रेफ़रेंस के माध्यम से
description: मास्टर स्लाइड्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imasterslidecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

मास्टर स्लाइड्स का एक संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्देशित सूचकांक पर तत्व को हटाता है। |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | अप्रयुक्त मास्टर स्लाइड्स को हटाता है। |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक कॉपी को संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने-योग्य [IMasterSlide](../../com.aspose.slides/imasterslide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | संग्रह से हटाने के लिए मास्टर स्लाइड। |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह के निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व का शून्य-आधारित सूचकांक। |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

अप्रयुक्त मास्टर स्लाइड्स को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ignorePreserveField | boolean | निर्धारित करता है कि क्या यह विधि अनउपयोगी मास्टर को हटाएगी, भले ही उसका [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) गुण true पर सेट हो। |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है। जुड़ी हुई लेआउट स्लाइड्स भी कॉपी किए जाएँगे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने के लिए स्लाइड। |

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - जोड़ी गई स्लाइड।
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक कॉपी को संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। जुड़ी हुई लेआउट स्लाइड्स भी कॉपी किए जाएंगे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का सूचकांक। |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने के लिए स्लाइड। |

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - सम्मिलित किया गया मास्टर स्लाइड।