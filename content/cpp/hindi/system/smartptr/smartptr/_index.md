---
title: SmartPtr()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: आवश्यक मोड का SmartPtr ऑब्जेक्ट बनाता है।
type: docs
weight: 1
url: /hi/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) निर्माता

आवश्यक मोड का [SmartPtr](../) ऑब्जेक्ट बनाता है।

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) निर्माता

आवश्यक मोड का null-pointer [SmartPtr](../) ऑब्जेक्ट बनाता है।

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | std::nullptr_t | पॉइंटर मोड। |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) निर्माता

निर्दिष्ट ऑब्जेक्ट की ओर इशारा करने वाला [SmartPtr](../) बनाता है, या raw pointer को [SmartPtr](../) में परिवर्तित करता है।

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | पॉइनी। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) निर्माता

कॉपी कंस्ट्रक्ट करके [SmartPtr](../) ऑब्जेक्ट बनाता है। दोनों पॉइंटर बाद में उसी ऑब्जेक्ट की ओर इशारा करते हैं।

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | कॉपी के लिए पॉइंटर। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) निर्माता

कॉपी कंस्ट्रक्ट करके [SmartPtr](../) ऑब्जेक्ट बनाता है। दोनों पॉइंटर बाद में उसी ऑब्जेक्ट की ओर इशारा करते हैं। यदि अनुमति हो तो प्रकार रूपांतरण करता है।

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | x द्वारा पॉइंट किए गए ऑब्जेक्ट का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | कॉपी के लिए पॉइंटर। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) निर्माता

मूव कंस्ट्रक्ट करके [SmartPtr](../) ऑब्जेक्ट बनाता है। प्रभावी रूप से, यदि दोनों एक ही मोड के हों तो दो पॉइंटर बदल देता है। कॉल के बाद x अनुपयोगी हो सकता है।

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | मूव के लिए पॉइंटर। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) निर्माता

एक अलग प्रकार की नई एरे बनाकर संदर्भित एरे के प्रकार को बदलता है। उपयोगी जब C# में एरे टाइप कास्ट हो जो C++ में असमर्थित है।

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | स्रोत एरे का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | एरे की कॉपी बनाते समय, लेकिन विभिन्न प्रकार के तत्वों के साथ, का पॉइंटर। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। |

## SmartPtr::SmartPtr(const Y\&) निर्माता

खाली एरे को इनिशियलाइज़ करता है। कुछ C# कोड निर्माणों का अनुवाद करने के लिए उपयोग किया जाता है।

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | EmptyArrayInitializer प्रकार का प्लेसहोल्डर। |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) निर्माता

एक [SmartPtr](../) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p को रखता है।

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | स्वामित्व को साझा करने वाले अन्य स्मार्ट पॉइंटर। |
| p | [Pointee_](../pointee_/) * | प्रबंधित करने के लिए ऑब्जेक्ट का पॉइंटर। |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर मोड। 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// यह क्लास एक फ़ील्ड रखती है जिसे प्रिंट किया जाएगा।
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// यह क्लास Foo क्लास की एक इंस्टेंस रखती है।
class Bar : public System::Object
{
public:
  Foo data;
};

// Foo-क्लास की इंस्टेंस से एक स्ट्रिंग प्रिंट करने के लिए उपयोग किया जाता है।
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// ऑब्जेक्ट की ओर इशारा करने वाले shared pointers की संख्या प्रिंट करता है।
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Bar क्लास की एक इंस्टेंस के लिए SharedPtr बनाएं।
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // SharedPtr बनाएं जो Bar-क्लास की इंस्टेंस के फ़ील्ड की ओर इशारा करेगा।
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 'bar' पॉइंटर को nullptr की ओर इशारा कराएं।
  bar.reset();
  PrintSharedCount(bar);
  // bar->data अभी भी मौजूद है और 'foo' पॉइंटर वैध है।
  PrintMessage(foo);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
साझा पॉइंटर्स की संख्या: 1
साझा पॉइंटर्स की संख्या: 2
साझा पॉइंटर्स की संख्या: 0
नमस्ते, दुनिया!
*/
``` |

## साथ देखें

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* क्लास [SmartPtr](../)
* क्लास [Array](../../array/)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)