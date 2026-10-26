---
title: SectionCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: सेक्शन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sectioncollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

सेक्शन का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड से शुरू होने वाला स्लाइड सेक्शन जोड़ें। |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | संग्रह के अंत में खाली सेक्शन जोड़ें। |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | संग्रह के निर्दिष्ट स्थान पर खाली सेक्शन जोड़ें। |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | संग्रह में निर्दिष्ट सेक्शन का अनुक्रमणिका लौटाता है। |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | सेक्शन और उसमें शामिल स्लाइड्स को हटाएँ। |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | सेक्शन हटाएँ। |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | सेक्शन और उसकी स्लाइड्स को संग्रह से हटाकर निर्दिष्ट स्थान पर ले जाएँ। |
| [clear()](#clear--) | संग्रह से सभी सेक्शन हटाएँ। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरा संग्रह निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण रूट लौटाता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह को इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरा संग्रह के लिए जावा इटरेटर लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISection](../../com.aspose.slides/isection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

निर्दिष्ट स्लाइड से शुरू होने वाला स्लाइड सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | सेक्शन की पहली स्लाइड |

**रिटर्न:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

संग्रह के अंत में खाली सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |

**रिटर्न:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

संग्रह के निर्दिष्ट स्थान पर खाली सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| index | int | नई सेक्शन का अनुक्रमणिका। |

**रिटर्न:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

संग्रह में निर्दिष्ट सेक्शन का अनुक्रमणिका लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | खोजने हेतु सेक्शन। |

**रिटर्न:**
int - सेक्शन का इंडेक्स या -1 यदि सेक्शन इस संग्रह से नहीं है।

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

सेक्शन और उसमें शामिल स्लाइड्स को हटाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने हेतु सेक्शन। |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

सेक्शन हटाएँ। सेक्शन में 포함된 स्लाइड्स को पिछले सेक्शन में मिलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने हेतु सेक्शन। |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

सेक्शन और उसकी स्लाइड्स को संग्रह से हटाकर निर्दिष्ट स्थान पर ले जाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ले जाने वाला सेक्शन। |
| index | int | लक्ष्य अनुक्रमणिका। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी सेक्शन हटाएँ।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरा संग्रह निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे |
| index | int | लक्षित एरे में इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह को इटरेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

पूरा संग्रह के लिए जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - पूरे संग्रह के लिए java.util.Iterator।