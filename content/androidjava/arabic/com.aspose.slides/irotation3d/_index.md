---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /ar/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

يمثل دورانًا ثلاثي الأبعاد للمخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRotationX()](#getRotationX--) | إرجاع أو تعيين درجة الدوران حول المحور X، أي |
| [setRotationX(byte value)](#setRotationX-byte-) | إرجاع أو تعيين درجة الدوران حول المحور X، أي |
| [getRotationY()](#getRotationY--) | إرجاع أو تعيين درجة الدوران حول المحور Y، أي |
| [setRotationY(int value)](#setRotationY-int-) | إرجاع أو تعيين درجة الدوران حول المحور Y، أي |
| [getPerspective()](#getPerspective--) | إرجاع أو تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | إرجاع أو تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | تحديد ما إذا كانت محاور المخطط بزاوية قائمة، بدلاً من رسمها بمنظور. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | تحديد ما إذا كانت محاور المخطط بزاوية قائمة، بدلاً من رسمها بمنظور. |
| [getDepthPercents()](#getDepthPercents--) | إرجاع أو تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 في المئة). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | إرجاع أو تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 في المئة). |
| [getHeightPercents()](#getHeightPercents--) | تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 في المئة). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 في المئة). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

إرجاع أو تعيين درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). الخاصية تتطابق مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع الخيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**الإرجاع:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

إرجاع أو تعيين درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). الخاصية تتطابق مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع الخيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

إرجاع أو تعيين درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). الخاصية تتطابق مع العنصر 21.2.2.158 rotY (Y Rotation) في ECMA-376 ومع الخيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**الإرجاع:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

إرجاع أو تعيين درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). الخاصية تتطابق مع العنصر 21.2.158 rotY (Y Rotation) في ECMA-376 ومع الخيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

إرجاع أو تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). يتم تجاهله إذا كانت الخاصية RightAngleAxes true. قراءة/كتابة byte.

**الإرجاع:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

إرجاع أو تعيين قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). يتم تجاهله إذا كانت الخاصية RightAngleAxes true. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

تحديد ما إذا كانت محاور المخطط بزاوية قائمة، بدلاً من رسمها بمنظور. بمعنى آخر، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

تحديد ما إذا كانت محاور المخطط بزاوية قائمة، بدلاً من رسمها بمنظور. بمعنى آخر، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

إرجاع أو تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 في المئة). قراءة/كتابة int.

**الإرجاع:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

إرجاع أو تعيين عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 في المئة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 في المئة). قراءة/كتابة int.

**الإرجاع:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

تحديد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 في المئة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |