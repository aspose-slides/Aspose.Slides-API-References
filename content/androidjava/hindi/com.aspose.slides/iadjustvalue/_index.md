---
title: IAdjustValue
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: ज्यामितीय आकार के समायोजन मान को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

ज्यामितीय आकार के समायोजन मान को दर्शाता है। ये मान आकार के रूप को प्रभावित करते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returns or sets adjustment value "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Returns or sets adjustment value "as is". |
| [getAngleValue()](#getAngleValue--) | Returns or sets value, interpreting it as angle in degrees. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returns or sets value, interpreting it as angle in degrees. |
| [getName()](#getName--) | Returns a name of this adjustment value. |
| [getType()](#getType--) | Returns the type of the shape adjustment. |

### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

समायोजन मान "जैसा है" को लौटाता है या सेट करता है। पढ़ें/लिखें long।

**रिटर्न:**
long

### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

समायोजन मान "जैसा है" को लौटाता है या सेट करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

कोण को डिग्री में व्याख्या करके मान को लौटाता है या सेट करता है। पढ़ें/लिखें float।

**रिटर्न:**
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

कोण को डिग्री में व्याख्या करके मान को लौटाता है या सेट करता है। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

इस समायोजन मान का नाम लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### getType() {#getType--}
```
public abstract int getType()
```

आकार के समायोजन का प्रकार लौटाता है। केवल-पढ़ने योग्य [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)।

**रिटर्न:**
int