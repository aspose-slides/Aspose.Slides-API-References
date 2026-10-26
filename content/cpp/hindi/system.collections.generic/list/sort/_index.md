---
title: Sort()
second_title: Aspose.Slides for C++ API संदर्भ
description: सूची में तत्वों को क्रमबद्ध करता है।
type: docs
weight: 521
url: /hi/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) विधि

सूची में तत्वों को क्रमबद्ध करता है।

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | उपयोग करने के लिए Comparator। |

## List::Sort() विधि

डिफ़ॉल्ट तुलना करने वाले का उपयोग करके सूची में तत्वों को क्रमबद्ध करता है।

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) विधि

सूची स्लाइस में तत्वों को क्रमबद्ध करता है।

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | स्लाइस की प्रारंभिक सूचकांक। |
| count | int | स्लाइस आकार। |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | उपयोग करने के लिए Comparator। |

## List::Sort(Comparison\<T\>, bool) विधि

सूची में तत्वों को क्रमबद्ध करता है।

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) को उपयोग करने के लिए। |

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComparer](../../icomparer/)
* क्लास [List](../)
* क्लास [Comparison](../../../system/comparison/)
* नेमस्पेस [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)