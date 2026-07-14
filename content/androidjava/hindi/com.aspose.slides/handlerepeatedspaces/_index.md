---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Android के जरिए Java API संदर्भ
description: यह निर्दिष्ट करता है कि बार-बार आने वाले नियमित स्पेस वर्णों को Markdown निर्यात के दौरान कैसे संभालना चाहिए।
type: docs
url: /hi/com.aspose.slides/handlerepeatedspaces/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

यह निर्दिष्ट करता है कि बार-बार आए नियमित स्पेस वर्ण को Markdown निर्यात के दौरान कैसे संभालना चाहिए।

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [None](#None) | सभी स्पेस को नियमित स्पेस वर्णों के रूप में बिना किसी परिवर्तन के संरक्षित किया जाता है। |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | दो या अधिक अनुक्रमित नियमित स्पेस को नियमित स्पेस वर्णों और non-breaking space entities NBSP के बीच वैकल्पिक रूप से परिवर्तित करता है। |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | दो या अधिक अनुक्रमित नियमित स्पेस को प्रथम स्पेस को नियमित स्पेस वर्ण के रूप में संरक्षित करके और सभी बाद के स्पेस को non-breaking space entities NBSP से बदलकर परिवर्तित करता है। |

### None {#None}
```
public static final int None
```

सभी स्पेस को नियमित स्पेस वर्णों के रूप में बिना किसी परिवर्तन के संरक्षित किया जाता है। कोई परिवर्तन लागू नहीं किया जाता है, और कई क्रमिक स्पेस को जैसा है वैसा निर्यात किया जाता है।

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

दो या अधिक अनुक्रमित नियमित स्पेस को नियमित स्पेस वर्णों और non-breaking space entities NBSP के बीच वैकल्पिक रूप से परिवर्तित करता है। पहला स्पेस हमेशा नियमित स्पेस के रूप में संरक्षित रहता है।

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

दो या अधिक अनुक्रमित नियमित स्पेस को प्रथम स्पेस को नियमित स्पेस वर्ण के रूप में संरक्षित करके और सभी बाद के स्पेस को non-breaking space entities NBSP से बदलकर परिवर्तित करता है।