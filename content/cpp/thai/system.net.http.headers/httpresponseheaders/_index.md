---
title: HttpResponseHeaders
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แสดงคอลเลกชันของส่วนหัว 'Response' เหลือออบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาด runtime และ/หรือการตรวจสอบความถูกต้องเสมอ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ในการส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 131
url: /th/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders คลาส

เป็นคอลเลกชันของส่วนหัว 'Response' Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | ตรวจสอบความถูกต้องของคู่ชื่อ-ค่าใหม่และเพิ่มเข้าไปในคอลเลกชันปัจจุบัน |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบความถูกต้องของคู่ชื่อ-ค่าใหม่และเพิ่มเข้าไปในคอลเลกชันปัจจุบัน |
| void [AddHeaders](./addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) override | ต่อเนื่องอินสแตนซ์ของคลาส HttpHeaders ที่ระบุกับอินสแตนซ์ปัจจุบัน |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | เพิ่มส่วนหัวที่รู้จักเข้าไปในคอลเลกชันที่ระบุ |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ดึงส่วนหัวตามชื่อที่ระบุและเพิ่มค่าที่แยกวิเคราะห์เข้ามาในส่วนหัว |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของคอลเลกชัน ตัว iterator นี้ไม่สามารถใช้เปลี่ยนแปลงอ็อบเจ็กต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบแรกที่มีคุณลักษณะ const (หากมี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ที่ชี้ตำแหน่งถัดจากองค์ประกอบสุดท้ายที่มีคุณลักษณะ const (หากมี) ของคอลเลกชัน |
| void [Clear](../httpheaders/clear/)() | ลบทุกรายการออกจากคอลเลกชัน |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ตรวจสอบว่าหัวส่วนหัวมีค่าที่ระบุหรือไม่ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ที่ชี้ตำแหน่งถัดจากองค์ประกอบสุดท้าย (หากมี) ของคอลเลกชัน ตัว iterator นี้ไม่สามารถใช้เปลี่ยนแปลงอ็อบเจ็กต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ที่ชี้ตำแหน่งถัดจากองค์ประกอบสุดท้าย (หากมี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_AcceptRanges](./get_acceptranges/)() | คืนค่าของส่วนหัว 'Accept-Ranges' |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_Age](./get_age/)() | คืนค่าของส่วนหัว 'Age' |
| [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\> [get_CacheControl](./get_cachecontrol/)() | คืนค่าของส่วนหัว 'Cache-Control' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Connection](./get_connection/)() | คืนค่าของส่วนหัว 'Connection' |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ConnectionClose](./get_connectionclose/)() | คืนค่าที่บ่งชี้ว่าค่าส่วนหัว 'Connection' มี 'Close' |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Date](./get_date/)() | คืนค่าของส่วนหัว 'Date' |
| [System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\> [get_ETag](./get_etag/)() | คืนค่าของส่วนหัว 'ETag' |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Location](./get_location/)() | คืนค่ของส่วนหัว 'Location' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Pragma](./get_pragma/)() | คืนค่าของส่วนหัว 'Pragma' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>\>\> [get_ProxyAuthenticate](./get_proxyauthenticate/)() | คืนค่าของส่วนหัว 'Proxy-Authenticate' |
| [System::SharedPtr](../../system/sharedptr/)\<[RetryConditionHeaderValue](../retryconditionheadervalue/)\> [get_RetryAfter](./get_retryafter/)() | คืนค่าของส่วนหัว 'Retry-After' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductInfoHeaderValue](../productinfoheadervalue/)\>\>\> [get_Server](./get_server/)() | คืนค่าของส่วนหัว 'Server' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Trailer](./get_trailer/)() | คืนค่ของส่วนหัว 'Trailer' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\> [get_TransferEncoding](./get_transferencoding/)() | คืนค่าของส่วนหัว 'Transfer-Encoding' |
| [Nullable](../../system/nullable/)\<**bool**\> [get_TransferEncodingChunked](./get_transferencodingchunked/)() | คืนค่าที่บ่งชี้ว่าค่าส่วนหัว 'Transfer-Encoding' มี 'Chunked' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](../productheadervalue/)\>\>\> [get_Upgrade](./get_upgrade/)() | คืนค่าของส่วนหัว 'Upgrade' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Vary](./get_vary/)() | คืนค่าของส่วนหัว 'Vary' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ViaHeaderValue](../viaheadervalue/)\>\>\> [get_Via](./get_via/)() | คืนค่าของส่วนหัว 'Via' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[WarningHeaderValue](../warningheadervalue/)\>\>\> [get_Warning](./get_warning/)() | คืนค่าของส่วนหัว 'Warning' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>\>\> [get_WwwAuthenticate](./get_wwwauthenticate/)() | คืนค่าของส่วนหัว 'WWW-Authenticate' |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | รับ enumerator |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ออนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของออบเจ็กต์ที่กำหนดเอง |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | คืนค่าการแสดงผลเป็นสตริงของค่าโดยใช้ชื่อส่วนหัวที่ระบุ |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | คืนค่าการแสดงผลเป็นสตริงของค่าโดยใช้ชื่อส่วนหัวที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | คืนคอลเลกชันที่บรรจุการแสดงผลเป็นสตริงของค่าของส่วนหัว |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | คืนค่าที่แยกวิเคราะห์โดยใช้ชื่อส่วนหัวที่ระบุ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ ออนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | คืนค่าที่สอดคล้องกันตามชื่อที่ระบุ |
|  [HttpResponseHeaders](./httpresponseheaders/)() | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType ออนาล็อกของตัวดำเนินการ C# 'is' |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ประยุกต์ฟังก์ชัน accumulator กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไข |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าโดยการเรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนขององค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนขององค์ประกอบในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ หรือค่าดีฟอลท์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไข หรือค่าดีฟอลท์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลท์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่ามากที่สุดที่ได้ |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำที่สุดที่ได้ |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับเพิ่มตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับลดตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | ทำการฉายแต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ออนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ ตั้งค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่คัดลอกอะไรจริง ๆ เพียงตั้งค่าออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่คัดลอกอะไรจริง ๆ เพียงตั้งค่าออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | แปลงค่าที่แยกวิเคราะห์เป็นรายการ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของออบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การสเปเชียลไลส์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การสเปเชียลไลส์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | พยายามลบรายการตามชื่อที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ดึงส่วนหัวตามชื่อที่ระบุและลบค่าที่แยกวิเคราะห์ออกจากส่วนหัว |
| void [set_Age](./set_age/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ตั้งค่าค่าส่วนหัว 'Age' |
| void [set_CacheControl](./set_cachecontrol/)([System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\>) | ตั้งค่าค่าส่วนหัว 'Cache-Control' |
| void [set_ConnectionClose](./set_connectionclose/)([Nullable](../../system/nullable/)\<**bool**\>) | ตั้งค่าที่บ่งชี้ว่าค่าส่วนหัว 'Connection' มี 'Close' |
| void [set_Date](./set_date/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าค่าส่วนหัว 'Date' |
| void [set_ETag](./set_etag/)([System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>) | ตั้งค่าค่าส่วนหัว 'ETag' |
| void [set_Location](./set_location/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ตั้งค่าค่าส่วนหัว 'Location' |
| void [set_RetryAfter](./set_retryafter/)([System::SharedPtr](../../system/sharedptr/)\<[RetryConditionHeaderValue](../retryconditionheadervalue/)\>) | ตั้งค่าค่าส่วนหัว 'Retry-After' |
| void [set_TransferEncodingChunked](./set_transferencodingchunked/)([Nullable](../../system/nullable/)\<**bool**\>) | ตั้งค่าที่บ่งชี้ว่าค่าส่วนหัว 'Transfer-Encoding' มี 'Chunked' |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ดึงส่วนหัวตามชื่อที่ระบุและตั้งค่าหรือถอดค่าของมัน ค่าของส่วนหัวจะถูกลบเมื่อพารามิเตอร์ 'value' เป็น nullptr มิฉะนั้นจะตั้งค่าที่แยกวิเคราะห์ |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ดึงส่วนหัวตามชื่อที่ระบุและตั้งค่าค่าที่แยกวิเคราะห์ให้กับส่วนหัว |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ลำดับที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | ออนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | พยายามเพิ่มคู่ชื่อ-ค่าใหม่เข้าไปในคอลเลกชันปัจจุบัน |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | เพิ่มคอลเลกชันของคู่ชื่อ-ค่าเข้าไปในคอลเลกชันปัจจุบัน |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | พยายามดึงค่าที่สอดคล้องตามชื่อที่ระบุ |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | พยายามแยกค่าที่ระบุและเพิ่มลงในค่าของส่วนหัว |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการนำไปใช้ของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการนำไปใช้ของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการนำไปใช้ของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการนำไปใช้ของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [HttpHeaders](../httpheaders/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)