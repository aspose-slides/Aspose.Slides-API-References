---
title: "System::Net::Security"
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 716
url: /ko/system.net.security/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | 이 클래스는 스트림을 통해 자격 증명을 전달하는 메서드를 포함합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 단언 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [SslStream](./sslstream/) | 서버와 선택적으로 클라이언트를 인증하기 위해 SSL 프로토콜을 사용하는 스트림입니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest 전용 인증 플래그. |
| [SslPolicyErrors](./sslpolicyerrors/) | SSL 정책 오류를 열거합니다. |
| [EncryptionPolicy](./encryptionpolicy/) | 암호화 정책을 열거합니다. |
## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | 원격 SSL 인증서를 검증하는 데 사용되는 사용자 대리자. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | 로컬 SSL 인증서를 선택하는 데 사용되는 사용자 대리자. |