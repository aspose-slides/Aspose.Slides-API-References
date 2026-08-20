---
title: HandleRepeatedSpaces
second_title: Aspose.Slides जावा API संदर्भ
description: निर्दिष्ट करता है कि मार्कडाउन निर्यात के दौरान दोहराए गए नियमित स्पेस कैरेक्टर को कैसे संभाला जाना चाहिए।
type: docs
url: /hi/com.aspose.slides/handlerepeatedspaces/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

निर्दिष्ट करता है कि दोहराए गए नियमित स्पेस कैरेक्टर को मार्कडाउन निर्यात के दौरान कैसे संभाला जाना चाहिए।
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [None](#None) | सभी स्पेस को बिना किसी परिवर्तन के नियमित स्पेस कैरेक्टर के रूप में संरक्षित किया जाता है। |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | दो या अधिक लगातार नियमित स्पेस की क्रमशः को नियमित स्पेस कैरेक्टर और नॉन-ब्रेकिंग स्पेस एंटिटी (NBSP) के बीच वैकल्पिक रूप से परिवर्तित करता है। |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | दो या अधिक लगातार नियमित स्पेस की क्रमशः को प्रथम स्पेस को नियमित स्पेस कैरेक्टर के रूप में संरक्षित रखते हुए, सभी आगे के स्पेस को नॉन-ब्रेकिंग स्पेस एंटिटी (NBSP) से बदल देता है। |
### None {#None}
```
public static final int None
```

सभी स्पेस को बिना किसी परिवर्तन के नियमित स्पेस कैरेक्टर के रूप में संरक्षित किया जाता है। कोई रूपांतरण लागू नहीं किया जाता, और कई लगातार स्पेस को जैसा है वैसा निर्यात किया जाता है।

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

दो या अधिक लगातार नियमित स्पेस की क्रमशः को नियमित स्पेस कैरेक्टर और नॉन-ब्रेकिंग स्पेस एंटिटी (NBSP) के बीच वैकल्पिक रूप से परिवर्तित करता है। पहला स्पेस हमेशा नियमित स्पेस के रूप में संरक्षित रहता है।

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

दो या अधिक लगातार नियमित स्पेस की क्रमशः को प्रथम स्पेस को नियमित स्पेस कैरेक्टर के रूप में संरक्षित रखते हुए, सभी आगे के स्पेस को नॉन-ब्रेकिंग स्पेस एंटिटी (NBSP) से बदल देता है।