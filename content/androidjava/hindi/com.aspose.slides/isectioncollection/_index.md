---
title: ISectionCollection
second_title: Aspose.Slides एंड्रॉइड के लिए Java API संदर्भ के माध्यम से
description: सेक्शन के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/isectioncollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

सेक्शन का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | विशिष्ट स्लाइड से शुरू होने वाला नया सेक्शन जोड़ता है। |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | संग्रह में निर्दिष्ट स्थिति पर खाली सेक्शन जोड़ता है। |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | सेक्शन और सेक्शन में शामिल स्लाइड्स को हटाता है। |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | सेक्शन को हटाता है। |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | सेक्शन और उसकी स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | संग्रह के अंत में खाली सेक्शन जोड़ता है। |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | संग्रह में निर्दिष्ट सेक्शन का इंडेक्स लौटाता है। |
| [clear()](#clear--) | संग्रह से सभी सेक्शन हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [ISection](../../com.aspose.slides/isection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

विशिष्ट स्लाइड से शुरू होने वाला नया सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | सेक्शन की पहली स्लाइड |

**वापसी:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

संग्रह में निर्दिष्ट स्थिति पर खाली सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |
| index | int | नए सेक्शन का इंडेक्स। |

**वापसी:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

सेक्शन और सेक्शन में शामिल स्लाइड्स को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने हेतु सेक्शन। |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

सेक्शन को हटाता है। सेक्शन में शामिल स्लाइड्स को पिछले सेक्शन में मिलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | संग्रह से हटाने हेतु सेक्शन। |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

सेक्शन और उसकी स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ले जाने हेतु सेक्शन। |
| index | int | लक्ष्य इंडेक्स। |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

संग्रह के अंत में खाली सेक्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेक्शन का नाम |

**वापसी:**
[ISection](../../com.aspose.slides/isection) - जोड़ा गया सेक्शन।
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

संग्रह में निर्दिष्ट सेक्शन का इंडेक्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | खोजने हेतु सेक्शन। |

**वापसी:**
int - सेक्शन का इंडेक्स या -1 यदि सेक्शन इस संग्रह से नहीं है।
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी सेक्शन हटाता है।