---
title: Task()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक कार्रवाई के साथ निष्पादित करने के लिए Task बनाता है।
type: docs
weight: 1
url: /hi/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) निर्माता

[Task](../) को एक कार्रवाई के साथ बनाता है जिसे असिंक्रोनस रूप से निष्पादित किया जाएगा।

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | असिंक्रोनस रूप से निष्पादित करने के लिए कार्रवाई |

## Task::Task(const Action<>\&, const CancellationToken\&) निर्माता

[Task](../) को एक कार्रवाई और रद्दीकरण टोकन के साथ बनाता है।

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | असिंक्रोनस रूप से निष्पादित करने के लिए कार्रवाई |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्दीकरण अनुरोधों की निगरानी के लिए टोकन |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) निर्माता

[Task](../) को एक स्टेटफुल कार्रवाई और स्टेट ऑब्जेक्ट के साथ बनाता है।

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | चलाने के लिए कार्रवाई (स्टेट ऑब्जेक्ट को स्वीकार करती है) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोगकर्ता-परिभाषित स्टेट ऑब्जेक्ट जिसे कार्रवाई को पास किया जाता है |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) निर्माता

[Task](../) को स्टेटफुल कार्रवाई, स्टेट, और रद्दीकरण टोकन के साथ बनाता है।

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | चलाने के लिए कार्रवाई (स्टेट ऑब्जेक्ट को स्वीकार करती है) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोगकर्ता-परिभाषित स्टेट ऑब्जेक्ट जिसे कार्रवाई को पास किया जाता है |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्दीकरण अनुरोधों की निगरानी के लिए टोकन |

## Task::Task() निर्माता

अनइनीशियलाइज़्ड टास्क बनाने के लिए आंतरिक निर्माता।

```cpp
System::Threading::Tasks::Task::Task()
```

## संबंधित देखें

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)