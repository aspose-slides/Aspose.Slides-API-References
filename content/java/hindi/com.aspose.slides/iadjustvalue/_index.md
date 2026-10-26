---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: एक ज्यामितीय आकार की समायोजन मान का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iadjustvalue/
---
```
public interface IAdjustValue
```

एक ज्यामितीय आकार की समायोजन मान का प्रतिनिधित्व करता है। ये मान आकार के रूप को प्रभावित करते हैं।
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

समायोजन मान को "as is" वापस देता है या सेट करता है। पढ़ने/लेखन long.

**वापसी:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

समायोजन मान को "as is" वापस देता है या सेट करता है। पढ़ने/लेखन long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

मान को वापस देता है या सेट करता है, इसे डिग्री में कोण के रूप में व्याख्या करता है। पढ़ने/लेखन float.

**वापसी:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

मान को वापस देता है या सेट करता है, इसे डिग्री में कोण के रूप में व्याख्या करता है। पढ़ने/लेखन float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

इस समायोजन मान का नाम वापस देता है। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

आकार समायोजन का प्रकार वापस देता है। केवल पढ़ने योग्य [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)।

**वापसी:**
int