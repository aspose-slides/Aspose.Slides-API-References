---
title: MathematicalText()
second_title: Aspose.Slides for C++ API 参考
description: "默认构造函数（创建 String::Empty 值）"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() 构造函数

默认构造函数（创建 String::Empty 值）

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## 备注

示例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) 构造函数

使用单个符号创建 [MathText](../../)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char16_t | 单个符号 |
## 备注

示例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) 构造函数

使用文本创建 [MathematicalText](../)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文本值 |
## 备注

示例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 构造函数

使用文本和格式设置创建 [MathematicalText](../)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文本值 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 文本格式设置 |
## 备注

示例： 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [MathematicalText](../)
* 类 [String](../../../system/string/)
* 类 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)