---
title: Shape()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "วนซ้ำแต่ละ ForEach::Shape ใน Presentation."
type: docs
weight: 40
url: /th/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) เมธอด


วนซ้ำแต่ละ [ForEach::Shape](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำรูปร่างการจัดวาง |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback ที่จะถูกเรียกสำหรับแต่ละ shape |
## หมายเหตุ


รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) และ [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) เมธอด


วนซ้ำแต่ละ [ForEach::Shape](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำรูปร่างการจัดวาง |
| includeNotes | **bool** | แฟลกที่ระบุว่า NotesSlides ควรรวมอยู่ในการประมวลผลหรือไม่ |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback ที่จะถูกเรียกสำหรับแต่ละ shape |
## หมายเหตุ


รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) และ [NotesSlide](../../../aspose.slides/notesslide/) หากต้องการ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) เมธอด


วนซ้ำแต่ละ [ForEach::Shape](./) ใน [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) เพื่อวนซ้ำรูปร่างการจัดวาง |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback ที่จะถูกเรียกสำหรับแต่ละ shape |
## หมายเหตุ


[BaseSlide](../../../aspose.slides/baseslide/) คือประเภทพื้นฐานสำหรับ [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) และ [ForEach::LayoutSlide](../layoutslide/)

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

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [ForEach](../)
* คลาส [BaseSlide](../../../aspose.slides/baseslide/)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)