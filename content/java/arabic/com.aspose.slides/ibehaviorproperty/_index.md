---
title: IBehaviorProperty
second_title: Aspose.Slides للمرجع API لجافا
description: تمثيل أنواع الخصائص لسلوك الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

تمثيل أنواع الخصائص لسلوك الرسوم المتحركة. يتبع قائمة الخصائص من https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx و https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | قيمة الخاصية |
| [isCustom()](#isCustom--) | يوضح ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المعرفة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```

قيمة الخاصية

**الإرجاع:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

يوضح ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المعرفة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**الإرجاع:**
boolean