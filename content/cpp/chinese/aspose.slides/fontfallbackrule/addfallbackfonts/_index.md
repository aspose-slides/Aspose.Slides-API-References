---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API 参考
description: 向回退字体列表中添加新的字体。
type: docs
weight: 79
url: /zh/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) 方法

向回退字体列表中添加新的字体。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 用于回退的字体名称或多个名称（逗号分隔） |
## 备注

```cpp
// 创建 FontFallBackRule 的新实例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//向规则添加第二个字体
newRule->AddFallBackFonts(u"MS Gothic");
//向规则添加第三个和第四个字体
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 方法

向回退字体列表中添加新的字体。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 用于回退的字体名称或多个名称（逗号分隔） |
## 备注

```cpp
// 创建 FontFallBackRule 的新实例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// 向规则添加另外三个字体
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [FontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)