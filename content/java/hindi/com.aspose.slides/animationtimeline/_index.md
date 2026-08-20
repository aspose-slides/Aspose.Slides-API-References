---
title: AnimationTimeLine
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एनिमेशन की टाइमलाइन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/animationtimeline/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)  
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

एनिमेशन की टाइमलाइन का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | इंटरैक्टिव अनुक्रमों का संग्रह लौटाता है। |
| [getMainSequence()](#getMainSequence--) | मुख्य अनुक्रम लौटाता है जिसमें केवल मुख्य प्रभावों का संग्रह हो सकता है। |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | टेक्स्ट एनीमेशनों का संग्रह लौटाता है। |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

इंटरैक्टिव अनुक्रमों का संग्रह लौटाता है। यह अनुक्रम केवल "click on shape" द्वारा निर्दिष्ट लक्ष्य आकार के साथ प्रभावों को शामिल कर सकता है। केवल पढ़ने योग्य [ISequenceCollection](../../com.aspose.slides/isequencecollection)।

**रिटर्न:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

मुख्य अनुक्रम लौटाता है जिसमें केवल मुख्य प्रभावों का संग्रह हो सकता है। केवल पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence)।

**रिटर्न:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

टेक्स्ट एनीमेशनों का संग्रह लौटाता है। केवल पढ़ने योग्य [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)।

**रिटर्न:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)