---
title: Rotation3D
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل دورانًا ثلاثيًا للمخطط.
type: docs
url: /ar/com.aspose.slides/rotation3d/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

يمثل دورانًا ثلاثيًا للمخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRotationX()](#getRotationX--) | يعيد أو يضبط درجة الدوران حول محور X، أي |
| [setRotationX(byte value)](#setRotationX-byte-) | يعيد أو يضبط درجة الدوران حول محور X، أي |
| [getRotationY()](#getRotationY--) | يعيد أو يضبط درجة الدوران حول محور Y، أي |
| [setRotationY(int value)](#setRotationY-int-) | يعيد أو يضبط درجة الدوران حول محور Y، أي |
| [getPerspective()](#getPerspective--) | يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | يحدد ما إذا كانت محاور المخطط بزاوٍ قائمة، بدلاً من رسمها في منظور. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | يحدد ما إذا كانت محاور المخطط بزاوٍ قائمة، بدلاً من رسمها في منظور. |
| [getDepthPercents()](#getDepthPercents--) | يعيد أو يضبط عمق مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمائة). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | يعيد أو يضبط عمق مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمائة). |
| [getHeightPercents()](#getHeightPercents--) | يحدد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمائة). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | يحدد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمائة). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

يعيد أو يضبط درجة الدوران حول محور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). تتطابق هذه الخاصية مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة بايت.

**القيمة المرجعة:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

يعيد أو يضبط درجة الدوران حول محور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). تتطابق هذه الخاصية مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة بايت.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

يعيد أو يضبط درجة الدوران حول محور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). تتطابق هذه الخاصية مع العنصر 21.2.2.158 rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

يعيد أو يضبط درجة الدوران حول محور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). تتطابق هذه الخاصية مع العنصر 21.2.2.158 rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 240). يتم تجاهلها إذا كانت قيمة خاصية RightAngleAxes هي true. قراءة/كتابة بايت.

**القيمة المرجعة:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 240). يتم تجاهلها إذا كانت قيمة خاصية RightAngleAxes هي true. قراءة/كتابة بايت.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

يحدد ما إذا كانت محاور المخطط بزاوٍ قائمة، بدلاً من رسمها في منظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

يحدد ما إذا كانت محاور المخطط بزاوٍ قائمة، بدلاً من رسمها في منظور. بعبارة أخرى، يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

يعيد أو يضبط عمق مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمائة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

يعيد أو يضبط عمق مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمائة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

يحدد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمائة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

يحدد ارتفاع مخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمائة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject