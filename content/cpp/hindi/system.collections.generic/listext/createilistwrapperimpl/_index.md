---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: IListWrapper कार्यान्वयन सहायक संदर्भ प्रकारों के लिए।
type: docs
weight: 14
url: /hi/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() मेथड


[IListWrapper](../../../system.collections/ilistwrapper/) संदर्भ प्रकारों के लिए कार्यान्वयन सहायक।

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() मेथड


[IListWrapper](../../../system.collections/ilistwrapper/) मान प्रकारों के लिए कार्यान्वयन सहायक।

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() मेथड


[IListWrapper](../../../system.collections/ilistwrapper/) अन्य प्रकारों के लिए कार्यान्वयन सहायक।

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IList](../../../system.collections/ilist/)
* क्लास [ListExt](../)
* स्ट्रक्ट [IsSmartPtr](../../../system/issmartptr/)
* स्ट्रक्ट [IsBoxable](../../../system/isboxable/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)