---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: एनीमेशन की टाइमलाइन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

एनीमेशन की टाइमलाइन का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | इंटरैक्टिव अनुक्रमों का संग्रह लौटाता है। |
| [getMainSequence()](#getMainSequence--) | मुख्य अनुक्रम लौटाता है जो केवल मुख्य प्रभावों के संग्रह को शामिल कर सकता है। |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | पाठ एनीमेशन का संग्रह लौटाता है। |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

इंटरैक्टिव अनुक्रमों का संग्रह लौटाता है। यह अनुक्रम केवल "click on shape" द्वारा प्रभावों को शामिल कर सकता है जिसमें निर्दिष्ट लक्ष्य आकार होता है। केवल-पढ़ने योग्य [ISequenceCollection](../../com.aspose.slides/isequencecollection)।

**रिटर्न:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

मुख्य अनुक्रम लौटाता है जो केवल मुख्य प्रभावों के संग्रह को शामिल कर सकता है। केवल-पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence)।

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

पाठ एनीमेशन का संग्रह लौटाता है। केवल-पढ़ने योग्य [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)।

**रिटर्न:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)