---
title: FontFallBackRule()
second_title: Aspose.Slides for C++ API 参考
description: 创建新实例。
type: docs
weight: 66
url: /zh/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) 构造函数


创建新实例。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 范围的起始索引 |
| endIndex | **uint32_t** | Unicode 范围的结束索引 |
| fontNames | [System::String](../../../system/string/) | FallBack 的字体名称或多个名称（逗号分隔） |
## 备注



```cpp
// 创建 FantFallBackRule 的新实例，使用一种字体。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// 创建 FantFallBackRule 的新实例，使用多种字体。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) 构造函数


创建新实例。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 范围的起始索引 |
| endIndex | **uint32_t** | Unicode 范围的结束索引 |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack 的字体名称或多个名称（逗号分隔） |
## 备注



```cpp
// 创建 FantFallBackRule 的新实例，使用两种字体
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// 创建 FantFallBackRule 的新实例，使用多种字体。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [FontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)