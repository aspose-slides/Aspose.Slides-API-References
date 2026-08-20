---
title: Rotation3D
second_title: مرجع API Aspose.Slides لجافا
description: يمثل دورانًا ثلاثي الأبعاد للمخطط.
type: docs
url: /ar/com.aspose.slides/rotation3d/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

يمثل دورانًا ثلاثي الأبعاد للمخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRotationX()](#getRotationX--) | يعيد أو يضبط درجة الدوران حول المحور X، أي |
| [setRotationX(byte value)](#setRotationX-byte-) | يعيد أو يضبط درجة الدوران حول المحور X، أي |
| [getRotationY()](#getRotationY--) | يعيد أو يضبط درجة الدوران حول المحور Y، أي |
| [setRotationY(int value)](#setRotationY-int-) | يعيد أو يضبط درجة الدوران حول المحور Y، أي |
| [getPerspective()](#getPerspective--) | يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). |
| [setPerspective(byte value)](#setPerspective-byte-) | يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | يحدد ما إذا كانت محاور المخطط قائمة بأزواٍ صحيحة، بدلاً من رسمها بمنظور. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | يحدد ما إذا كانت محاور المخطط قائمة بأزواٍ صحيحة، بدلاً من رسمها بمنظور. |
| [getDepthPercents()](#getDepthPercents--) | يعيد أو يضبط عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمئة). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | يعيد أو يضبط عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمئة). |
| [getHeightPercents()](#getHeightPercents--) | يحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمئة). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | يحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمئة). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

يعيد أو يضبط درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). تتطابق الخاصية مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**القيمة المرجعة:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

يعيد أو يضبط درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و90 درجة). تتطابق الخاصية مع العنصر 21.2.2.157 rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

يعيد أو يضبط درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). تتطابق الخاصية مع العنصر 21.2.2.158 rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

يعيد أو يضبط درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و360 درجة). تتطابق الخاصية مع العنصر 21.2.2.158 rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 200...

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). يتم تجاهلها إذا كانت قيمة خاصية RightAngleAxes هي true. قراءة/كتابة byte.

**القيمة المرجعة:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

يعيد أو يضبط قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و240). يتم تجاهلها إذا كانت قيمة خاصية RightAngleAxes هي true. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

يحدد ما إذا كانت محاور المخطط قائمة بأزواٍ صحيحة، بدلاً من رسمها بمنظور. بعبارة أخرى يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران المخطط أو ارتفاعه. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

يحدد ما إذا كانت محاور المخطط قائمة بأزواٍ صحيحة، بدلاً من رسمها بمنظور. بعبارة أخرى يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران المخطط أو ارتفاعه. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

يعيد أو يضبط عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمئة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

يعيد أو يضبط عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و2000 بالمئة). قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

يحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمئة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

يحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و500 بالمئة). قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject