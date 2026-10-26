---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 1080
url: /zh-hant/system.web.services.protocols/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | 表示在透過 SOAP 呼叫方法時拋出的例外，且發生錯誤。切勿手動建立此類別的實例。請改用 SoapException 類別。切勿將 SoapException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | 此基底類別用於所有使用 HTTP 的 XML [Web](../system.web/) 服務客戶端代理。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | 此類別的實例將作為參數傳遞給 InvokeCompletedEventHandler 委派。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapClientMessage](./soapclientmessage/) | 表示已傳送的 SOAP 請求或已接收的 SOAP 回應中的資料。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | 指定所有從方法傳遞或返回的 SOAP 訊息使用 Document 格式。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | 設定 SOAP 請求與回應的預設格式。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapHeader](./soapheader/) | 表示 SOAP 標頭的內容。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapHeaderAttribute](./soapheaderattribute/) | 指定 XML [Web](../system.web/) 服務方法或 XML [Web](../system.web/) 服務客戶端能處理的 SOAP 標頭。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapHeaderCollection](./soapheadercollection/) | 包含 [SoapHeader](./soapheader/) 類別之實例的集合。 |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | 在使用 SOAP 時，客戶端代理服務必須繼承此類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SoapMessage](./soapmessage/) | 表示 SOAP 訊息。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebClientProtocol](./webclientprotocol/) | 此基底類別用於所有使用 ASP.NET 建立的 XML [Web](../system.web/) 服務客戶端代理。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |

## 列舉

| 列舉 | 描述 |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | 列舉 SOAP 標頭方向。 |
| [SoapMessageStage](./soapmessagestage/) | 列舉 SOAP 訊息的處理階段。 |
| [SoapParameterStyle](./soapparameterstyle/) | 列舉 SOAP 訊息中參數的格式。 |
| [SoapProtocolVersion](./soapprotocolversion/) | 列舉 SOAP 的版本。 |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | 列舉 SOAP 訊息路由至 XML [Web](../system.web/) 服務的選項。 |

## 型別定義

| 型別定義 | 描述 |
| --- | --- |
| [SoapException](./soapexception/) |  |