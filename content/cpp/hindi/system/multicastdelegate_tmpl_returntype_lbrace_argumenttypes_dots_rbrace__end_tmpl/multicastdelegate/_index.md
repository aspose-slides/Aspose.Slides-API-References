---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक खाली संग्रह बनाता है।
type: docs
weight: 1
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

एक खाली संग्रह बनाता है।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

डिफॉल्ट कंस्ट्रक्टर के बराबर है।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

डेलीगेट संग्रह की उथली प्रतिलिपि बनाता है।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | const MulticastDelegate\& | An instance of MulticastDelegate class to copy the collection of delegates from. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

मूविंग कंस्ट्रक्टर।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | MulticastDelegate\&& | An instance of MulticastDelegate class to move the collection of delegates from. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

एक इंस्टेंस बनाता है और निर्दिष्ट डेलीगेट को डेलीगेट संग्रह में जोड़ता है।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | A delegate to put to the delegate collection |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

एक इंस्टेंस बनाता है और निर्दिष्ट मान को डेलीगेट संग्रह में जोड़ता है।

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | Type of the value to put to the delegate collection of the newly constructed instance; the type must be convertible to Callback type. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg | T | A value to put to the delegate collection |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

एक इंस्टेंस बनाता है और निर्दिष्ट मान को डेलीगेट संग्रह में जोड़ता है।

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | A value to put to the delegate collection |

## देखिए

* Typedef [Callback](../callback/)
* क्लास [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)