---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Reference
description: 表示動畫行為的屬性類型。
type: docs
url: /zh-hant/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

表示動畫行為的屬性類型。依照以下屬性清單：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 和 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## 方法

| 方法 | 說明 |
| --- | --- |
| [getValue()](#getValue--) | 屬性的值 |
| [isCustom()](#isCustom--) | 顯示此屬性是否不屬於規範中預先定義的屬性清單：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |

### getValue() {#getValue--}
```
public abstract String getValue()
```

屬性的值

**傳回:**  
java.lang.String

### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

顯示此屬性是否不屬於規範中預先定義的屬性清單：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**傳回:**  
boolean