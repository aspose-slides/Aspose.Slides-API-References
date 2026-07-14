---
title: IParagraphFormat
second_title: Aspose.Slides for Android عبر Java API Reference
description: هذه الفئة تحتوي على خصائص تنسيق الفقرة.
type: docs
url: /ar/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

هذه الفئة تحتوي على خصائص تنسيق الفقرة. على عكس [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع وتعديل خصائص تنسيق الفقرة المحددة للفقرة المعنية. يعني ذلك عدم تطبيق الوراثة عند جلب القيم، لذلك في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم المعلمات التنسيق الفعالة بما في ذلك الموروثة، تحتاج إلى استخدام الطريقة [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) التي تُرجع كائن [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBullet()](#getBullet--) | يُعيد تنسيق الرصاص للفقرة. |
| [getDepth()](#getDepth--) | يُعيد أو يضبط عمق الفقرة. |
| [setDepth(short value)](#setDepth-short-) | يُعيد أو يضبط عمق الفقرة. |
| [getAlignment()](#getAlignment--) | يُعيد أو يضبط محاذاة النص في فقرة دون وراثة. |
| [setAlignment(int value)](#setAlignment-int-) | يُعيد أو يضبط محاذاة النص في فقرة دون وراثة. |
| [getSpaceWithin()](#getSpaceWithin--) | يُعيد أو يضبط مقدار المسافة بين خطوط القاعدة في فقرة. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | يُعيد أو يضبط مقدار المسافة بين خطوط القاعدة في فقرة. |
| [getSpaceBefore()](#getSpaceBefore--) | يُعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة دون وراثة. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | يُعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة دون وراثة. |
| [getSpaceAfter()](#getSpaceAfter--) | يُعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | يُعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | يحدد ما إذا كان يُستخدم كسر السطر شرق آسيوي في الفقرة. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | يحدد ما إذا كان يُستخدم كسر السطر شرق آسيوي في الفقرة. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان يُستخدم الكتابة من اليمين إلى اليسار في الفقرة. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | يحدد ما إذا كان يُستخدم الكتابة من اليمين إلى اليسار في الفقرة. |
| [getLatinLineBreak()](#getLatinLineBreak--) | يحدد ما إذا كان يُستخدم كسر السطر اللاتيني في الفقرة. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | يحدد ما إذا كان يُستخدم كسر السطر اللاتيني في الفقرة. |
| [getHangingPunctuation()](#getHangingPunctuation--) | يحدد ما إذا كان يُستخدم ترقيم علامات الترقيم المتدلية في الفقرة. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | يحدد ما إذا كان يُستخدم ترقيم علامات الترقيم المتدلية في الفقرة. |
| [getMarginLeft()](#getMarginLeft--) | يُعيد أو يضبط الهامش الأيسر في فقرة دون وراثة. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | يُعيد أو يضبط الهامش الأيسر في فقرة دون وراثة. |
| [getMarginRight()](#getMarginRight--) | يُعيد أو يضبط الهامش الأيمن في فقرة دون وراثة. |
| [setMarginRight(float value)](#setMarginRight-float-) | يُعيد أو يضبط الهامش الأيمن في فقرة دون وراثة. |
| [getIndent()](#getIndent--) | يُعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. |
| [setIndent(float value)](#setIndent-float-) | يُعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. |
| [getDefaultTabSize()](#getDefaultTabSize--) | يُعيد أو يضبط حجم التبويب الافتراضي دون وراثة. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | يُعيد أو يضبط حجم التبويب الافتراضي دون وراثة. |
| [getTabs()](#getTabs--) | يُعيد تبويبات الفقرة. |
| [getFontAlignment()](#getFontAlignment--) | يُعيد أو يضبط محاذاة الخط في فقرة دون وراثة. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | يُعيد أو يضبط محاذاة الخط في فقرة دون وراثة. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | يُعيد تنسيق الجزء الافتراضي للفقرة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الفقرة الفعالة مع تطبيق الوراثة. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

يُعيد تنسيق الرصاص للفقرة. للقراءة فقط [IBulletFormat](../../com.aspose.slides/ibulletformat).

**الإرجاع:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

يُعيد أو يضبط عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة short.

**الإرجاع:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

يُعيد أو يضبط عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة short.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

يُعيد أو يضبط محاذاة النص في فقرة دون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

**الإرجاع:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

يُعيد أو يضبط محاذاة النص في فقرة دون وراثة. قراءة/كتابة [TextAlignment](../../com.aspose.slides/textalignment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

يُعيد أو يضبط مقدار المسافة بين خطوط القاعدة في فقرة. القيمة الموجبة تعني نسبة مئوية، السالبة تعني الحجم بالنقاط. لا تُطبق وراثة. قراءة/كتابة float.

**الإرجاع:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

يُعيد أو يضبط مقدار المسافة بين خطوط القاعدة في فقرة. القيمة الموجبة تعني نسبة مئوية، السالبة تعني الحجم بالنقاط. لا تُطبق وراثة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

يُعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة بالنقاط. قراءة/كتابة float.

**الإرجاع:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

يُعيد أو يضبط مقدار المسافة قبل السطر الأول في فقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة بالنقاط. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

يُعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة بالنقاط. قراءة/كتابة float.

**الإرجاع:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

يُعيد أو يضبط مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. القيمة الموجبة تحدد النسبة المئوية لحجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السالبة تحدد حجم المسافة بالنقاط. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

يحدد ما إذا كان يُستخدم كسر السطر شرق آسيوي في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

يحدد ما إذا كان يُستخدم كسر السطر شرق آسيوي في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

يحدد ما إذا كان يُستخدم الكتابة من اليمين إلى اليسار في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

يحدد ما إذا كان يُستخدم الكتابة من اليمين إلى اليسار في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

يحدد ما إذا كان يُستخدم كسر السطر اللاتيني في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

يحدد ما إذا كان يُستخدم كسر السطر اللاتيني في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

يحدد ما إذا كان يُستخدم ترقيم علامات الترقيم المتدلية في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

يحدد ما إذا كان يُستخدم ترقيم علامات الترقيم المتدلية في الفقرة. لا تُطبق وراثة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

يُعيد أو يضبط الهامش الأيسر في فقرة دون وراثة. قراءة/كتابة float.

**الإرجاع:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

يُعيد أو يضبط الهامش الأيسر في فقرة دون وراثة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

يُعيد أو يضبط الهامش الأيمن في فقرة دون وراثة. قراءة/كتابة float.

**الإرجاع:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

يُعيد أو يضبط الهامش الأيمن في فقرة دون وراثة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

يُعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. قراءة/كتابة float.

**الإرجاع:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

يُعيد أو يضبط إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

يُعيد أو يضبط حجم التبويب الافتراضي دون وراثة. قراءة/كتابة float.

**الإرجاع:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

يُعيد أو يضبط حجم التبويب الافتراضي دون وراثة. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

يُعيد تبويبات الفقرة. لا تُطبق وراثة. للقراءة فقط [ITabCollection](../../com.aspose.slides/itabcollection).

**الإرجاع:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

يُعيد أو يضبط محاذاة الخط في فقرة دون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**الإرجاع:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

يُعيد أو يضبط محاذاة الخط في فقرة دون وراثة. قراءة/كتابة [FontAlignment](../../com.aspose.slides/fontalignment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

يُعيد تنسيق الجزء الافتراضي للفقرة. لا تُطبق وراثة. للقراءة فقط [IPortionFormat](../../com.aspose.slides/iportionformat).

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الفقرة الفعالة مع تطبيق الوراثة.

**الإرجاع:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).