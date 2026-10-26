---
title: "System::Net::Http"
second_title: Aspose.Slides for C++ API-referencia
description: 
type: docs
weight: 677
url: /hu/system.net.http/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | HTTP tartalmat képviseli bájt tömbként. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [Details_HttpRequestException](./details_httprequestexception/) | Az alap kivétel osztályt a(z) [HttpClient](./httpclient/) és [HttpMessageHandler](./httpmessagehandler/) osztályok dobják. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a HttpRequestException osztályt. Soha ne csomagolja be a HttpRequestException osztály példányait [System::SmartPtr](../system/smartptr/)-be. |
| [HttpClient](./httpclient/) | HTTP kliens alap osztályát képviseli a kérések küldéséhez és a válaszok fogadásához. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpClientHandler](./httpclienthandler/) | Az alapértelmezett üzenetkezelőt képviseli, amelyet a(z) [HttpClient](./httpclient/) osztály használ. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpContent](./httpcontent/) | HTTP entitás tartalmát képviseli. Ennek az osztálynak a(z) [Object](../system/object/) csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpMessageHandler](./httpmessagehandler/) | HTTP üzenetkezelők alap típusát képviseli. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Lehetővé teszi az alkalmazások számára, hogy meghívják a Send metódust egy HTTP kezelő láncon. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpMethod](./httpmethod/) | HTTP metódust képviseli. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpRequestMessage](./httprequestmessage/) | HTTP kérés üzenetet képviseli. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpResponseMessage](./httpresponsemessage/) | HTTP válasz üzenetet képviseli. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
| [HttpUtilities](./httputilities/) | Tartalmazza a segédmetódusokat. |
| [StringContent](./stringcontent/) | HTTP tartalmat képviseli karakterláncként. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezt a típust a stackon vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadásra a függvényeknek. |
## Függvények

| Függvény | Leírás |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Enumerációk

| Enumeráció | Leírás |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Jelzi, hogy egy [HttpClient](./httpclient/) művelet mikor fejeződjön be. |
| [HttpParseResult](./httpparseresult/) | Jelzi a feldolgozás eredményét. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |