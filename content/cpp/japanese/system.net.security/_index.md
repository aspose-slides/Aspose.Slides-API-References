---
title: "System::Net::Security"
second_title: Aspose.Slides の C++ API リファレンス
description: 
type: docs
weight: 716
url: /ja/system.net.security/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | ストリーム間で資格情報を渡すためのメソッドを含みます。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション障害が発生する可能性があります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [SslStream](./sslstream/) | SSL プロトコルを使用してサーバーを認証し、必要に応じてクライアントも認証するストリームです。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest 固有の認証フラグです。 |
| [SslPolicyErrors](./sslpolicyerrors/) | SSL のポリシーエラーを列挙します。 |
| [EncryptionPolicy](./encryptionpolicy/) | 暗号化ポリシーを列挙します。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | リモート SSL 証明書の検証に使用されるユーザーデリゲートです。 |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | ローカル SSL 証明書の選択に使用されるユーザーデリゲートです。 |