---
title: MasterSlideCollection
second_title: Aspose.Slides for Java API संदर्भ
description: मास्टर स्लाइड्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/masterslidecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)  
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

मास्टर स्लाइड्स का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में उपस्थित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | संग्रह से किसी विशिष्ट वस्तु की पहली आवृत्ति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | अप्रयुक्त मास्टर स्लाइड्स को हटाता है। |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़ (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
| [iterator()](#iterator--) | एक एन्उमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में उपस्थित तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int.

**वापसी मान:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [MasterSlide](../../com.aspose.slides/masterslide).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

संग्रह से किसी विशिष्ट वस्तु की पहली आवृत्ति को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | संग्रह से हटाने हेतु मास्टर स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने हेतु तत्व का शून्य-आधारित अनुक्रमांक। |

--------------------

PptxEditException को थ्रो होने से रोकने के लिये, मास्टर की HasDependingSlides प्रॉपर्टी को पहले जांचें। |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

अप्रयुक्त मास्टर स्लाइड्स को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ignorePreserveField | boolean | निर्धारित करता है कि यह विधि उस स्थिति में भी अप्रयुक्त मास्टर को हटाएगी जब उसका [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) प्रॉपर्टी true पर सेट हो। |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। जुड़ी हुई लेआउट स्लाइड्स भी कॉपी हो जाएँगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने हेतु स्लाइड। |

**वापसी मान:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - जोड़ी गई स्लाइड।

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

निर्दिष्ट मास्टर स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर सम्मिलित करता है। जुड़ी हुई लेआउट स्लाइड्स भी कॉपी हो जाएँगी।

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // स्रोत प्रस्तुति फ़ाइल लोड करने के लिए Presentation क्लास को इंस्टैंशिएट करें
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // गंतव्य प्रस्तुति (जहाँ स्लाइड क्लोन की जाएगी) के लिए Presentation क्लास को इंस्टैंशिएट करें
>      Presentation destPres = new Presentation();
>      try {
>          // स्रोत प्रस्तुति में स्लाइड्स के संग्रह से ISlide को इंस्टैंशिएट करें, साथ में
>          // मास्टर स्लाइड
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // गंतव्य प्रस्तुति की मास्टर स्लाइड्स प्राप्त करें
>          IMasterSlideCollection masters = destPres.getMasters();
>          // स्रोत प्रस्तुति से इच्छित मास्टर स्लाइड को गंतव्य प्रस्तुति के मास्टर संग्रह में क्लोन करें,
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


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | क्लोन करने हेतु स्लाइड। |

**वापसी मान:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - सम्मिलित किया गया मास्टर स्लाइड।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़ (थ्रेड-सुरक्षित) है या नहीं। केवल पढ़ने योग्य boolean.

**वापसी मान:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल पढ़ने योग्य Object.

**वापसी मान:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

एक एन्उमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है।

**वापसी मान:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - संग्रह को इटरिट करने के लिये उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**वापसी मान:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - पूरे संग्रह के लिये java.util.Iterator।