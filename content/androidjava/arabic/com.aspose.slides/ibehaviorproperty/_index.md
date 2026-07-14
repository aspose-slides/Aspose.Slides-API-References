---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /ar/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

تمثيل أنواع الخصائص لسلوك الرسوم المتحركة. Follows the list of properties from https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx and https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | قيمة الخاصية |
| [isCustom()](#isCustom--) | يظهر ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المحددة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
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

يظهر ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المحددة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**الإرجاع:**  
boolean