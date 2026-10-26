---
title: ResultTask
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक टास्क विशेषीकरण जो पूर्णता पर परिणाम मान लौटाता है।
type: docs
weight: 40
url: /hi/system.threading.tasks/resulttask/
---
## ResultTask क्लास

एक [Task](../task/) विशेषीकरण जो पूर्णता पर एक परिणाम मान लौटाता है।

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टास्क द्वारा लौटाए गए परिणाम मान का प्रकार |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | एक शेड्यूलर पर कार्य को निष्पादित करने के लिए सक्रिय करता है। |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | पूरा होने पर निष्पादित होने के लिए एक निरंतरता कार्य जोड़ता है। |
| void [Cancel](../task/cancel/)() | टास्क को रद्द के रूप में चिह्नित करता है और टास्क को समाप्त करता है। |
| void [Complete](./complete/)(const T\&) | टास्क के लिए परिणाम मान सेट करता है और इसे पूरा करता है। |
| void [Complete](../task/complete/)() | टास्क को पूर्ण के रूप में चिह्नित करता है और टास्क को समाप्त करता है। |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | इस परिणाम टास्क पर प्रतीक्षा करने के तरीके को कॉन्टेक्स्ट कैप्चर के संबंध में कॉन्फ़िगर करता है। |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | एक निरंतरता बनाता है जो परिणाम टास्क के पूरा होने पर निष्पादित होती है। |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | एक निरंतरता बनाता है जो परिणाम टास्क के पूरा होने पर निष्पादित होती है। |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | एक निरंतरता बनाता है जो टास्क के पूरा होने पर निष्पादित होती है। |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | एक निरंतरता बनाता है जो टास्क के पूरा होने पर निष्पादित होती है। |
| void [Deactivate](../task/deactivate/)() | यदि कोई हो तो वर्तमान शेड्यूलर पर कार्य निष्पादन को निष्क्रिय करता है। |
| void [Dispose](../task/dispose/)() override | टास्क से संबंधित संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| void [Execute](../task/execute/)() | टास्क के फ़ंक्शन को निष्पादित करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | टास्क से जुड़े उपयोगकर्ता-परिभाषित स्टेट ऑब्जेक्ट को प्राप्त करता है। |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | एक पूर्ण टास्क (सिंगलटन) प्राप्त करता है। |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | टास्क के ID को प्राप्त करता है। |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | क्या टास्क रद्दीकरण के कारण पूर्ण हुआ है, प्राप्त करता है। |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | क्या टास्क पूर्ण हुआ है, प्राप्त करता है। |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | क्या टास्क अनहैंडल्ड एक्सेप्शन के कारण पूर्ण हुआ है, प्राप्त करता है। |
| T [get_Result](./get_result/)() | असमकालिक संचालन के परिणाम को प्राप्त करता है। |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | इस टास्क से जुड़े शेड्यूलर को प्राप्त करता है। |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | टास्क की वर्तमान स्थिति को प्राप्त करता है। |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | इस परिणाम टास्क के लिए Await के साथ उपयोग हेतु एक awaiter प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आभ्यंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपवर्गों के कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपवर्गों के कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | [ResultTask](./) को एक फ़ंक्शन के साथ बनाता है जो मान लौटाता है। |
|  [ResultTask](./resulttask/)() | आंतरिक कार्यान्वयन। उपयोगकर्ता कोड के लिए नहीं। |
|  [ResultTask](./resulttask/)(const T\&) | निर्धारित परिणाम के साथ परिणाम टास्क बनाने के लिए आंतरिक कन्स्ट्रक्टर। |
| void [RunSynchronously](../task/runsynchronously/)() | वर्तमान थ्रेड पर टास्क को सिंक्रोनस रूप से चलाता है। |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | निर्दिष्ट शेड्यूलर का उपयोग करके टास्क को सिंक्रोनस रूप से चलाता है। |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | चलाने के लिए आन्तरिक फ़ंक्शन सेट करता है। |
| void [set_Result](./set_result/)(const T\&) | टास्क के परिणाम मान को सेट करता है। |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | इस टास्क से जुड़े शेड्यूलर को सेट करता है। |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | टास्क की स्थिति सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Start](../task/start/)() | डिफ़ॉल्ट शेड्यूलर का उपयोग करके टास्क निष्पादन शुरू करता है। |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | निर्दिष्ट शेड्यूलर का उपयोग करके टास्क निष्पादन शुरू करता है। |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | [Task](../task/) को एक कार्य के साथ बनाता है जिसे निष्पादित किया जाएगा। |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | [Task](../task/) को एक कार्य और कैंसेलेशन टोकन के साथ बनाता है। |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | [Task](../task/) को एक स्टेटफुल कार्य और स्टेट ऑब्जेक्ट के साथ बनाता है। |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | [Task](../task/) को स्टेटफुल कार्य, स्टेट और कैंसेलेशन टोकन के साथ बनाता है। |
|  [Task](../task/task/)() | अनइनिशियलाइज़्ड टास्क बनाने के लिए आन्तरिक कन्स्ट्रक्टर। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | कैंसेलेशन समर्थन के साथ टास्क के पूर्ण होने की प्रतीक्षा करता है। |
| void [Wait](../task/wait/)() | टास्क के पूर्ण होने की प्रतीक्षा करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीेक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीेक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आन्तरिक डेटा संरचनाओं को मुक्त करता है। |
|  [~Task](../task/~task/)() | डिस्ट्रक्टर। |
## टिप्पणी

एक असिंक्रोनस ऑपरेशन को दर्शाता है जो परिणाम उत्पन्न करता है, जैसा कि .NET में System.Threading.Tasks.Task<TResult> के समान है।

## देखें

* क्लास [Task](../task/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)