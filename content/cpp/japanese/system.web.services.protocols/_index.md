---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 1080
url: /ja/system.web.services.protocols/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | SOAP を介してメソッドが呼び出されたときにエラーが発生した場合にスローされる例外を表します。このクラスのインスタンスを手動で作成しないでください。代わりに SoapException クラスを使用してください。SoapException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | この基底クラスは HTTP を使用するすべての XML [Web](../system.web/) サービスクライアントプロキシで使用されます。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | このクラスのインスタンスは InvokeCompletedEventHandler デリゲートへの引数として渡されます。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapClientMessage](./soapclientmessage/) | 送信された SOAP リクエストまたは受信した SOAP レスポンスのデータを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | メソッドから渡されたり返されたりするすべての SOAP メッセージが Document 形式を使用することを指定します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | SOAP リクエストおよびレスポンスのデフォルト形式を設定します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapHeader](./soapheader/) | SOAP ヘッダーの内容を表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapHeaderAttribute](./soapheaderattribute/) | XML [Web](../system.web/) サービスメソッドまたは XML [Web](../system.web/) サービスクライアントが処理できる SOAP ヘッダーを指定します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapHeaderCollection](./soapheadercollection/) | [SoapHeader](./soapheader/) クラスのインスタンスのコレクションを含みます。 |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | SOAP が使用される場合、クライアントプロキシサービスはこのクラスを継承しなければなりません。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SoapMessage](./soapmessage/) | SOAP メッセージを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [WebClientProtocol](./webclientprotocol/) | この基底クラスは ASP.NET を使用して作成されたすべての XML [Web](../system.web/) サービスクライアントプロキシで使用されます。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上または operator new で作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | SOAP ヘッダーの方向を列挙します。 |
| [SoapMessageStage](./soapmessagestage/) | SOAP メッセージの処理段階を列挙します。 |
| [SoapParameterStyle](./soapparameterstyle/) | SOAP メッセージ内のパラメータ形式を列挙します。 |
| [SoapProtocolVersion](./soapprotocolversion/) | SOAP のバージョンを列挙します。 |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | SOAP メッセージが XML [Web](../system.web/) サービスにルーティングされる方法のオプションを列挙します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [SoapException](./soapexception/) |  |