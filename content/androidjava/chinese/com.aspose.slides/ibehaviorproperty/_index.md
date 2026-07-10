---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画行为的属性类型。
type: docs
url: /zh/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

表示动画行为的属性类型。遵循以下属性列表：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 和 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 属性的值 |
| [isCustom()](#isCustom--) | 显示此属性是否不属于规范中预定义属性列表: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```

属性的值

**返回:**  
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

显示此属性是否不属于规范中预定义属性列表: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**返回:**  
boolean