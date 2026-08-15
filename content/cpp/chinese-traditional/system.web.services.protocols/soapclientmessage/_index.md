---
title: SoapClientMessage
second_title: Aspose.Slides for C++ API 參考文件
description: "表示已發送的 SOAP 請求或已接收的 SOAP 回應中的資料。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 40
url: /zh-hant/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage 類別

表示已發送的 SOAP 請求或已接收的 SOAP 回應中的資料。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## 方法

| Method | 描述 |
| --- | --- |
| void [CollectHeaders](../soapmessage/collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | 設定 SOAP 標頭的內部集合。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](../soapmessage/findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | 依指定的標頭類型尋找標頭映射。 |
| [String](../../system/string/) [get_Action](./get_action/)() override | 返回 'SOAPAction' 屬性的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\> [get_Client](./get_client/)() | 返回客戶端代理類別的實例。 |
| [String](../../system/string/) [get_ContentEncoding](../soapmessage/get_contentencoding/)() | 取得 'Content-Encoding' 標頭的值。 |
| [String](../../system/string/) [get_ContentType](../soapmessage/get_contenttype/)() | 取得 'Content-Type' 標頭的值。 |
| [SoapException](../soapexception/) [get_Exception](../soapmessage/get_exception/)() | 取得 XML [Web](../../system.web/) 服務方法拋出的例外。 |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](../soapmessage/get_headers/)() | 返回 SOAP 標頭的集合。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](../soapmessage/get_inparameters/)() | 取得傳入 XML [Web](../../system.web/) 服務方法的參數。 |
| **bool** [get_IsSoap12](../soapmessage/get_issoap12/)() | 返回指示是否使用 SOAP 1.2 版的值。 |
| virtual **bool** [get_OneWay](./get_oneway/)() | 返回指示客戶端是否不等待伺服器完成方法處理的值。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](../soapmessage/get_outparameters/)() | 取得傳入 XML [Web](../../system.web/) 服務方法的輸出參數。 |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() override | 返回使用的 SOAP 版本。 |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](../soapmessage/get_stage/)() | 取得 SOAP 訊息的處理階段。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](../soapmessage/get_stream/)() | 取得包含 SOAP 訊息資料的串流。 |
| [String](../../system/string/) [get_Url](./get_url/)() override | 返回 XML [Web](../../system.web/) 服務的 URL。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](../soapmessage/getinparametervalue/)(**int32_t**) | 取得指定索引處的輸入參數值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](../soapmessage/getoutparametervalue/)(**int32_t**) | 取得指定索引處的輸出參數值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](../soapmessage/getreturnvalue/)() | 取得 XML [Web](../../system.web/) 服務方法的返回值。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 做參考比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_ContentEncoding](../soapmessage/set_contentencoding/)([String](../../system/string/)) | 設定 'Content-Encoding' 標頭的值。 |
| void [set_ContentType](../soapmessage/set_contenttype/)([String](../../system/string/)) | 設定 'Content-Type' 標頭的值。 |
| void [set_InParameters](../soapmessage/set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | 設定傳入 XML [Web](../../system.web/) 服務方法的參數。 |
| void [set_InternalStream](../soapmessage/set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 設定包含 SOAP 訊息資料的串流。 |
| void [set_OutParameters](../soapmessage/set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | 設定傳入 XML [Web](../../system.web/) 服務方法的輸出參數。 |
| void [SetException](../soapmessage/setexception/)([SoapException](../soapexception/)) | 設定 XML [Web](../../system.web/) 服務方法拋出的例外。 |
| void [SetHeaders](../soapmessage/setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | 設定 SOAP 標頭的集合。 |
| void [SetStage](../soapmessage/setstage/)([SoapMessageStage](../soapmessagestage/)) | 設定 SOAP 訊息的處理階段。 |
| void [SetStream](../soapmessage/setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 設定包含 SOAP 訊息資料的串流。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
|  [SoapClientMessage](./soapclientmessage/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapMethodStubInfo\>, [String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | 建立新的實例。 |
|  [SoapMessage](../soapmessage/soapmessage/)() | 建立新的實例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| void [UpdateHeaderValues](../soapmessage/updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | 更新 SOAP 標頭的內部集合。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [SoapMessage](../soapmessage/)
* 命名空間 [System::Web::Services::Protocols](../)
* 程式庫 [Aspose.Slides](../../)