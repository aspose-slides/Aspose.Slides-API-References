---
title: ILayoutSlideCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: लेआउट स्लाइड्स के संग्रह के लिए एक आधार वर्ग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilayoutslidecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

लेआउट स्लाइड्स के संग्रह के लिए एक आधार वर्ग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा लेआउट स्लाइड लौटाता है। |
| [getByType(byte type)](#getByType-byte-) | निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है। |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | संग्रह से एक लेआउट हटाता है। |
| [removeUnused()](#removeUnused--) | बिना उपयोग किए गए लेआउट स्लाइड्स हटाता है (जिन लेआउट स्लाइड्स की HasDependingSlides false है)। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

इंडेक्स द्वारा लेआउट स्लाइड लौटाता है। केवल-पढ़ने-योग्य [ILayoutSlide](../../com.aspose.slides/ilayoutslide)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | byte | खोजने के लिए लेआउट स्लाइड का प्रकार। |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) निर्दिष्ट प्रकार के साथ या यदि कोई लेआउट नहीं मिला तो null।

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

संग्रह से एक लेआउट हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | संग्रह से हटाने के लिए लेआउट स्लाइड। |

--------------------

1) PptxEditException को फेंकने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें। 2) कोड को सरल बनाने के लिए आप [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) मेथड का भी उपयोग कर सकते हैं। |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

बिना उपयोग किए गए लेआउट स्लाइड्स हटाता है (जिन लेआउट स्लाइड्स की HasDependingSlides false है)।