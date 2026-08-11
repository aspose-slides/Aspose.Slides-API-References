---
title: AddAudio()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف نسخة من ملف صوتي من عرض تقديمي آخر.
type: docs
weight: 53
url: /ar/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) طريقة

يضيف نسخة من ملف صوتي من عرض تقديمي آخر.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | ملف الصوت المصدر. |

### قيمة الإرجاع

الصوت المُضاف.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الذي يُضاف منه الصوت. |

### قيمة الإرجاع

الصوت المُضاف.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة

ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الذي يُضاف منه صوت الفيديو. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيُطبق على التدفق. |

### قيمة الإرجاع

الصوت المُضاف.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) طريقة

ينشئ ويضيف صوتًا إلى عرض تقديمي من مصفوفة بايت.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بايتات [Audio](../../audio/). |

### قيمة الإرجاع

الصوت المُضاف.

## انظر أيضًا

* تعداد [LoadingStreamBehavior](../../loadingstreambehavior/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IAudio](../../iaudio/)
* فئة [AudioCollection](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)