---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API 参考
description: 获取将在演示文稿渲染时被替换的字体信息。
type: docs
weight: 66
url: /zh/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() 方法

获取将在演示文稿渲染时被替换的字体的信息。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### 返回值

所有字体替换的集合 [FontSubstitutionInfo](../../fontsubstitutioninfo/)。

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) 方法

获取将在指定幻灯片渲染期间被替换的字体的信息。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 一个数组，包含从 1 开始的幻灯片索引，用于检索字体替换信息。 |

### 返回值

指定幻灯片的所有字体替换集合 ([FontSubstitutionInfo](../../fontsubstitutioninfo/))。

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* 类 [IFontsManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)