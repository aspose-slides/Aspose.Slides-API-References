---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API संदर्भ
description: एनीमेशन की टाइमलाइन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

एनीमेशन की टाइमलाइन का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

इंटरएक्टिव अनुक्रमों का संग्रह लौटाता है। यह अनुक्रम केवल "आकार पर क्लिक" द्वारा निर्दिष्ट लक्ष्य आकार के प्रभावों को ही रख सकता है। केवल-रीड [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**वापसी:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

मुख्य अनुक्रम लौटाता है जो केवल मुख्य प्रभाव संग्रह को ही रख सकता है। केवल-रीड [ISequence](../../com.aspose.slides/isequence).

**वापसी:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

टेक्स्ट एनीमेशन का संग्रह लौटाता है। केवल-रीड [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**वापसी:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)