---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ API 参考
description: 向回退字体列表中添加一个或多个新字体。
type: docs
weight: 40
url: /zh/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) 方法

向回退字体列表中添加一个或多个新字体。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 回退字体的名称或多个名称（以逗号分隔） |
## 备注

```cpp
//创建 FantFallBackRule 的新实例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//向规则添加第二种字体
newRule->AddFallBackFonts(u"MS Gothic");
//向规则添加第三种和第四种字体
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 方法

向回退字体列表中添加新字体。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 回退字体的名称或多个名称（以逗号分隔） |
## 备注

```cpp
//创建 FontFallBackRule 的新实例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//向规则添加另外三个字体
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [IFontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)