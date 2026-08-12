---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 365
url: /hi/system.collections.generic.details.castrules/
---
## संरचनाएँ

| संरचना | विवरण |
| --- | --- |
| [CastType](./casttype/) | कास्ट प्रकार निर्धारित करने के लिए फ़ंक्शन शामिल हैं। |
## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत और परिणाम प्रकार समान हों। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत प्रकार को स्थिर रूप से परिणाम प्रकार में कास्ट किया जा सकता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब प्रकार समान न हों और स्रोत प्रकार को स्थिर रूप से परिणाम प्रकार में कास्ट नहीं किया जा सकता। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत प्रकार को [Nullable](../system/nullable/) क्लास इंस्टेंस में बॉक्स किया जा रहा हो। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत प्रकार को [Nullable](../system/nullable/) क्लास इंस्टेंस से अनबॉक्स किया जा रहा हो। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत प्रकार को [Object](../system/object/) क्लास इंस्टेंस में बॉक्स किया जा रहा हो। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब स्रोत प्रकार को [Object](../system/object/) क्लास इंस्टेंस से अनबॉक्स किया जा रहा हो। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। उपयोग तब होता है जब कास्टिंग अमान्य हो या रूपांतरण स्पष्ट हो। |
| **bool** [IsNull](./isnull/)(T) | जाँचता है कि प्रस्तुत मान nullptr है। |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | जाँचता है कि प्रस्तुत मान nullptr है। |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | जाँचता है कि प्रस्तुत मान nullptr है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | कास्ट की संभावनाओं की जाँच करता है। |