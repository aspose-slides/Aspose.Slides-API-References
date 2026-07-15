---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: 表示動畫行為的屬性類型。
type: docs
url: /zh-hant/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

表示動畫行為的屬性類型。遵循來自 https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 和 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx 的屬性清單
## 方法

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | 屬性的值 |
| [isCustom()](#isCustom--) | 顯示此屬性是否不屬於規範中預定義屬性列表： https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


屬性的值

**返回：**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


顯示此屬性是否不屬於規範中預定義屬性列表： https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**返回：**
boolean