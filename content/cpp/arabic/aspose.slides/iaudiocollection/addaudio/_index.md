---
title: AddAudio()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف نسخة من ملف صوتي من عرض تقديمي آخر.
type: docs
weight: 14
url: /ar/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) طريقة


يضيف نسخة من ملف صوتي من عرض تقديمي آخر.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | صوت المصدر. |

### القيمة المرجعة

الصوت المضاف.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) طريقة


ينشئ ويضيف صوتًا إلى عرض تقديمي من التدفق.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق لإضافة الصوت منه. |

### القيمة المرجعة

الصوت المضاف.

## مهمل
:   استخدم AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). سيتم إزالة الطريقة في الإصدار 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة


ينشئ ويضيف صوتًا إلى عرض تقديمي من التدفق.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق لإضافة فيديو صوت منه. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيُطبق على التدفق. |

### القيمة المرجعة

الصوت المضاف.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) طريقة


ينشئ ويضيف صوتًا إلى عرض تقديمي من مصفوفة بايت.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) بايت. |

### القيمة المرجعة

الصوت المضاف.

## انظر أيضًا

* تعداد [LoadingStreamBehavior](../../loadingstreambehavior/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IAudio](../../iaudio/)
* فئة [IAudioCollection](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)