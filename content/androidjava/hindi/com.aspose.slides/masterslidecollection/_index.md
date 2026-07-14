---
title: MasterSlideCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: मास्टर स्लाइड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/masterslidecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)  
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Represents a collection of master slides.

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | संग्रह से किसी विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | अपर्युक्त मास्टर स्लाइड्स को हटाता है। |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट सरणी में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच सिंक्रनाइज़ (थ्रेड-सुरक्षित) है। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
| [iterator()](#iterator--) | एक ए़न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [MasterSlide](../../com.aspose.slides/masterslide).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

संग्रह से किसी विशिष्ट वस्तु की पहली घटना को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | संग्रह से हटाने के लिए मास्टर स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व का शून्य-आधारित सूचकांक। |

--------------------

PptxEditException को थ्रो होने से बचने के लिए, मास्टर की HasDependingSlides प्रॉपर्टी को पहले जांचें। |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

अपर्युक्त मास्टर स्लाइड्स को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ignorePreserveField | boolean | निर्धारित करता है कि क्या यह मेथड उन अपर्युक्त मास्टर को भी हटाएगा यदि उसकी [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) प्रॉपर्टी true पर सेट है। |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। जुड़े हुए लेआउट स्लाइड्स भी कॉपी किए जाएंगे।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने के लिए स्लाइड। |

**रिटर्न:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - जोड़ा गया स्लाइड।

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर सम्मिलित करता है। जुड़े हुए लेआउट स्लाइड्स भी कॉपी किए जाएंगे।

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // स्रोत प्रस्तुति फ़ाइल को लोड करने के लिए Presentation क्लास का इंस्टेंस बनाएं
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // गंतव्य प्रस्तुति (जहाँ स्लाइड को क्लोन किया जाएगा) के लिए Presentation क्लास का इंस्टेंस बनाएं
>      Presentation destPres = new Presentation();
>      try {
>          // स्रोत प्रस्तुति में स्लाइड्स के संग्रह से ISlide को इंस्टेंस बनाएं, साथ में
>          // मास्टर स्लाइड
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // गंतव्य प्रस्तुति की मास्टर स्लाइड्स प्राप्त करें
>          IMasterSlideCollection masters = destPres.getMasters();
>          // स्रोत प्रस्तुति से इच्छित मास्टर स्लाइड को मास्टर संग्रह में क्लोन करें
>          // गंतव्य प्रस्तुति
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // गंतव्य प्रस्तुति में स्लाइड्स का संग्रह
>          ISlideCollection slds = destPres.getSlides();
>          // स्रोत स्लाइड को गंतव्य स्लाइड संग्रह में क्लोन करें।
>          slds.addClone(SourceSlide, iSlide, true);
>          // गंतव्य प्रस्तुति को डिस्क पर सहेजें
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का सूचकांक। |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने के लिए स्लाइड। |

**रिटर्न:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - सम्मिलित मास्टर स्लाइड।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट सरणी में कॉपी करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित सरणी। |
| index | int | लक्षित सरणी में आरंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच सिंक्रनाइज़ (थ्रेड-सुरक्षित) है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object.

**रिटर्न:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

एक ए़न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.