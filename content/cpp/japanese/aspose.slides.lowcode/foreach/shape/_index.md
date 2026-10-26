---
title: Shape()
second_title: Aspose.Slides for C++ APIリファレンス
description: "プレゼンテーション内の各 ForEach::Shape を反復処理します。"
type: docs
weight: 40
url: /ja/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) メソッド

各[ForEach::Shape](./)を[Presentation](../../../aspose.slides/presentation/)で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) はレイアウトシェイプを反復するための |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 各シェイプに対して呼び出されるコールバック |
## 備考

すべてのスライドタイプのシェイプが反復されます - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) と [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) メソッド

各[ForEach::Shape](./)を[Presentation](../../../aspose.slides/presentation/)で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) はレイアウトシェイプを反復するための |
| includeNotes | **bool** | NotesSlides を処理に含めるかどうかを示すフラグ |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 各シェイプに対して呼び出されるコールバック |
## 備考

すべてのスライドタイプのシェイプが反復されます - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) と [NotesSlide](../../../aspose.slides/notesslide/) が必要に応じて

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) メソッド

各[ForEach::Shape](./)を[BaseSlide](../../../aspose.slides/baseslide/)で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) はレイアウトシェイプを反復するための |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 各シェイプに対して呼び出されるコールバック |
## 備考

[BaseSlide](../../../aspose.slides/baseslide/) は [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) と [ForEach::LayoutSlide](../layoutslide/) の基本型です

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

ForEach::Slide(pres, std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)
    {
        System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), shapeIndex);
    };

    auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)>(lambda);

    ForEach::Shape(slide, callback);
}));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Class [BaseSlide](../../../aspose.slides/baseslide/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)