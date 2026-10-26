---
title: WarningType
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक चेतावनी प्रकार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/warningtype/
---
**Inheritance:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

एक चेतावनी प्रकार का प्रतिनिधित्व करता है।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | स्रोत दस्तावेज़ में एक समस्या का पता चला है जिससे यह बहुत संभावना है कि यदि इसे उसके मूल स्वरूप में सहेजा जाए तो दस्तावेज़ को खोला नहीं जा सकेगा। |
| [DataLoss](#DataLoss) | लोड के बाद दस्तावेज़ ट्री में या सहेजने के बाद बनाए गए दस्तावेज़ में टेक्स्ट/चार्ट/छवि या अन्य डेटा पूरी तरह से अनुपलब्ध रहेगा। |
| [MajorFormattingLoss](#MajorFormattingLoss) | गंभीर फ़ॉर्मेटिंग हानि। |
| [MinorFormattingLoss](#MinorFormattingLoss) | छोटी फ़ॉर्मेटिंग हानि। |
| [CompatibilityIssue](#CompatibilityIssue) | यह ज्ञात समस्या है जो कुछ उपयोगकर्ता एजेंटों या उनके पिछले संस्करणों द्वारा दस्तावेज़ को खोलने से रोक देगी। |
| [UnexpectedContent](#UnexpectedContent) | स्रोत दस्तावेज़ में कुछ सामग्री को पहचाना नहीं जा सका (जैसे |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

स्रोत दस्तावेज़ में एक समस्या का पता चला है जिससे यह बहुत संभावना है कि यदि इसे उसके मूल स्वरूप में सहेजा जाए तो दस्तावेज़ को खोला नहीं जा सकेगा।

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

लोड के बाद दस्तावेज़ ट्री में या सहेजने के बाद बनाए गए दस्तावेज़ में टेक्स्ट/चार्ट/छवि या अन्य डेटा पूरी तरह से अनुपलब्ध रहेगा।

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

गंभीर फ़ॉर्मेटिंग हानि।

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

छोटी फ़ॉर्मेटिंग हानि।

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

यह ज्ञात समस्या है जो कुछ उपयोगकर्ता एजेंटों या उनके पिछले संस्करणों द्वारा दस्तावेज़ को खोलने से रोक देगी।

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

स्रोत दस्तावेज़ में कुछ सामग्री को पहचाना नहीं जा सका (जैसे असमर्थित), यह समस्याएँ पैदा कर सकता है या नहीं भी, और डेटा/फ़ॉर्मेटिंग हानि का कारण बन सकता है।