---
title: SectionCollection
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: सेक्शन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sectioncollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

सेक्शन के संग्रह का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड से शुरू होने वाला स्लाइड सेक्शन जोड़ता है। |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | संग्रह के अंत में खाली सेक्शन जोड़ता है। |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | संग्रह में निर्दिष्ट स्थिति पर खाली सेक्शन जोड़ता है। |
| [size()](#size--) | संग्रह में वास्तव में मौज़ूद तत्वों की संख्या प्राप्त करता है। |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | संग्रह में निर्दिष्ट सेक्शन का इंडेक्स लौटाता है। |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | सेक्शन और उस में मौजूद स्लाइड्स को हटाता है। |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | सेक्शन हटाता है। |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | सेक्शन और उसकी स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। |
| [clear()](#clear--) | संग्रह से सभी सेक्शन हटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। |
| [iterator()](#iterator--) | एक एनेमेरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISection](../../com.aspose.slides/isection).

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

वापसी:
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

निर्दिष्ट स्लाइड से शुरू होने वाला स्लाइड सेक्शन जोड़ता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | सेक्शन की पहली स्लाइड |

वापसी:
[ISection](../../com.aspose.slides/isection) - जोड़ित सेक्शन।

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

संग्रह के अंत में खाली सेक्शन जोड़ता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |

वापसी:
[ISection](../../com.aspose.slides/isection) - जोड़ित सेक्शन।

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

संग्रह में निर्दिष्ट स्थिति पर खाली सेक्शन जोड़ता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| index | int | नए सेक्शन का इंडेक्स। |

वापसी:
[ISection](../../com.aspose.slides/isection) - जोड़ित सेक्शन।

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौज़ूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

वापसी:
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

संग्रह में निर्दिष्ट सेक्शन का इंडेक्स लौटाता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | खोजने के लिए सेक्शन। |

वापसी:
int - सेक्शन का इंडेक्स या -1 यदि सेक्शन इस संग्रह से नहीं है।

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

सेक्शन और उस में मौजूद स्लाइड्स को हटाता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने के लिए सेक्शन। |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

सेक्शन हटाता है। सेक्शन में मौजूद स्लाइड्स को पिछले सेक्शन में मर्ज किया जाएगा।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने के लिए सेक्शन। |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

सेक्शन और उसकी स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ले जाने वाला सेक्शन। |
| index | int | लक्ष्य इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी सेक्शन हटाता है।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है।

पैरामीटर:
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे |
| index | int | लक्षित एरे में इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं यह दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य boolean।

वापसी:
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। केवल-पढ़ने योग्य Object।

वापसी:
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

एक एनेमेरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

वापसी:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - वह IGenericEnumerator जो संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

वापसी:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - पूरे संग्रह के लिए एक java.util.Iterator।