---
title: HttpRequestHeaders
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นตัวแทนของคอลเลกชันของส่วนหัว 'Request' วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 118
url: /th/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders คลาส

เป็นตัวแทนของคอลเลกชันของส่วนหัว 'Request' วัตถุของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | ตรวจสอบคู่ชื่อ-ค่าใหม่และเพิ่มเข้าไปในคอลเลกชันปัจจุบัน |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบคู่ชื่อ-ค่าใหม่และเพิ่มเข้าไปในคอลเลกชันปัจจุบัน |
| void [AddHeaders](./addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) override | ต่อเชื่อมอินสแตนซ์ของคลาส HttpHeaders ที่ระบุกับอันปัจจุบัน |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | เพิ่มส่วนหัวที่รู้จักลงในคอลเลกชันที่ระบุ |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | รับส่วนหัวตามชื่อที่ระบุและเพิ่มค่าที่แปรผลลงในส่วนหัว |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรก (หากมี) ของคอลเลกชัน ไม่สามารถใช้อิเทอเรเตอร์นี้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) ส่งคืนวัตถุสำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรก (หากมี) ของอินสแตนซ์ที่กำหนดค่า const ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรกที่กำหนดค่า const (หากมี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์ const สุดท้าย (หากมี) ของคอลเลกชัน |
| void [Clear](../httpheaders/clear/)() | ลบรายการทั้งหมดออกจากคอลเลกชัน |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ตรวจสอบว่าหัวส่วนหัวมีค่าที่ระบุหรือไม่ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์สุดท้าย (หากมี) ของคอลเลกชัน ไม่สามารถใช้อิเทอเรเตอร์นี้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) ส่งคืนวัตถุสำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์สุดท้าย (หากมี) ของอินสแตนซ์ที่กำหนดค่า const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](../mediatypewithqualityheadervalue/)\>\>\> [get_Accept](./get_accept/)() | ส่งคืนค่าของส่วนหัว 'Accept' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptCharset](./get_acceptcharset/)() | ส่งคืนค่าของส่วนหัว 'Accept-Charset' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptEncoding](./get_acceptencoding/)() | ส่งคืนค่าของส่วนหัว 'Accept-Encoding' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptLanguage](./get_acceptlanguage/)() | ส่งคืนค่าของส่วนหัว 'Accept-Language' |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_Authorization](./get_authorization/)() | รับค่าของส่วนหัว 'Authorization' |
| [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\> [get_CacheControl](./get_cachecontrol/)() | รับค่าของส่วนหัว 'Cache-Control' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Connection](./get_connection/)() | ส่งคืนค่าของส่วนหัว 'Connection' |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ConnectionClose](./get_connectionclose/)() | รับค่าที่บ่งบอกว่าค่าของส่วนหัว 'Connection' มี 'Close' หรือไม่ |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Date](./get_date/)() | รับค่าของส่วนหัว 'Date' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../namevaluewithparametersheadervalue/)\>\>\> [get_Expect](./get_expect/)() | ส่งคืนค่าของส่วนหัว 'Expect' |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ExpectContinue](./get_expectcontinue/)() | รับค่าที่บ่งบอกว่าค่าของส่วนหัว 'Expect' มี 'Continue' หรือไม่ |
| [String](../../system/string/) [get_From](./get_from/)() | รับค่าของส่วนหัว 'From' |
| [String](../../system/string/) [get_Host](./get_host/)() | รับค่าของส่วนหัว 'Host' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfMatch](./get_ifmatch/)() | ส่งคืนค่าของส่วนหัว 'If-Match' |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfModifiedSince](./get_ifmodifiedsince/)() | รับค่าของส่วนหัว 'If-Modified-Since' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfNoneMatch](./get_ifnonematch/)() | ส่งคืนค่าของส่วนหัว 'If-None-Match' |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\> [get_IfRange](./get_ifrange/)() | รับค่าของส่วนหัว 'If-Range' |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | รับค่าของส่วนหัว 'If-Unmodified-Since' |
| [Nullable](../../system/nullable/)\<**int32_t**\> [get_MaxForwards](./get_maxforwards/)() | รับค่าของส่วนหัว 'Max-Forwards' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Pragma](./get_pragma/)() | ส่งคืนค่าของส่วนหัว 'Pragma' |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_ProxyAuthorization](./get_proxyauthorization/)() | รับค่าของส่วนหัว 'Proxy-Authorization' |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\> [get_Range](./get_range/)() | รับค่าของส่วนหัว '[Range](../../system/range/)' |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Referrer](./get_referrer/)() | รับค่าของส่วนหัว 'Referer' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingWithQualityHeaderValue](../transfercodingwithqualityheadervalue/)\>\>\> [get_TE](./get_te/)() | ส่งคืนค่าของส่วนหัว 'TE' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Trailer](./get_trailer/)() | ส่งคืนค่าของส่วนหัว 'Trailer' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\> [get_TransferEncoding](./get_transferencoding/)() | ส่งคืนค่าของส่วนหัว 'Transfer-Encoding' |
| [Nullable](../../system/nullable/)\<**bool**\> [get_TransferEncodingChunked](./get_transferencodingchunked/)() | รับค่าที่บ่งบอกว่าค่าของส่วนหัว 'Transfer-Encoding' มี 'Chunked' หรือไม่ |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](../productheadervalue/)\>\>\> [get_Upgrade](./get_upgrade/)() | ส่งคืนค่าของส่วนหัว 'Upgrade' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductInfoHeaderValue](../productinfoheadervalue/)\>\>\> [get_UserAgent](./get_useragent/)() | ส่งคืนค่าของส่วนหัว 'User-Agent' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ViaHeaderValue](../viaheadervalue/)\>\>\> [get_Via](./get_via/)() | ส่งคืนค่าของส่วนหัว 'Via' |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[WarningHeaderValue](../warningheadervalue/)\>\>\> [get_Warning](./get_warning/)() | ส่งคืนค่าของส่วนหัว 'Warning' |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | รับ enumerator |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดให้ทำการแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | ส่งคืนสตริงที่เป็นตัวแทนของค่าตามชื่อส่วนหัวที่ระบุ |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ส่งคืนสตริงที่เป็นตัวแทนของค่าตามชื่อส่วนหัวที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | ส่งคืนคอลเลกชันที่มีสตริงเป็นตัวแทนของค่าห้องส่วนหัว |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | ส่งคืนค่าที่แปรผลตามชื่อส่วนหัวที่ระบุ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | ส่งคืนค่าที่สอดคล้องตามชื่อที่ระบุ |
|  [HttpRequestHeaders](./httprequestheaders/)() | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าควรอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายตัวดำเนินการ C# 'is' |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | ตรวจสอบว่าอิลิเมนต์ทั้งหมดของลำดับตรงตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | ตรวจสอบว่าลำดับมีอิลิเมนต์ใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | ตรวจสอบว่ามีอิลิเมนต์ใดในลำดับที่ตรงกับเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทของอิลิเมนต์เป็นชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเชื่อมลำดับสองรายการ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | ส่งคืนจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนจำนวนอิลิเมนต์ในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | ส่งคืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | ส่งคืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | ส่งคืนอิลิเมนต์แรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | ส่งคืนอิลิเมนต์แรกของลำดับ หรือค่ามาตรฐานหากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | ส่งคืนอิลิเมนต์แรกของลำดับที่ตรงกับเงื่อนไข หรือค่ามาตรฐานหากไม่พบอิลิเมนต์ใด |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มอิลิเมนต์ของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มอิลิเมนต์ของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | ส่งคืนอิลิเมนต์สุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | ส่งคืนอิลิเมนต์สุดท้ายของลำดับ หรือค่ามาตรฐานหากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและส่งคืนค่าที่ได้สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและส่งคืนค่าที่ได้ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับลดตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | สลับลำดับของอิลิเมนต์ในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงอิลิเมนต์ของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีของอิลิเมนต์ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โพรเจกต์แต่ละอิลิเมนต์ของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามอิลิเมนต์ต่อเนื่องจำนวนที่ระบุจากจุดเริ่มต้นของลำดับและส่งคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | ส่งคืนจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดให้ทำการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | แปลงค่าที่แปรผลเป็นรายการ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | พยายามลบรายการโดยใช้ชื่อที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | รับส่วนหัวตามชื่อที่ระบุและลบค่าที่แปรผลออกจากส่วนหัว |
| void [set_Authorization](./set_authorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | ตั้งค่าของส่วนหัว 'Authorization' |
| void [set_CacheControl](./set_cachecontrol/)([System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\>) | ตั้งค่าของส่วนหัว 'Cache-Control' |
| void [set_ConnectionClose](./set_connectionclose/)([Nullable](../../system/nullable/)\<**bool**\>) | ตั้งค่าที่บ่งบอกว่าค่าของส่วนหัว 'Connection' มี 'Close' หรือไม่ |
| void [set_Date](./set_date/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าของส่วนหัว 'Date' |
| void [set_ExpectContinue](./set_expectcontinue/)([Nullable](../../system/nullable/)\<**bool**\>) | ตั้งค่าที่บ่งบอกว่าค่าของส่วนหัว 'Expect' มี 'Continue' หรือไม่ |
| void [set_From](./set_from/)([String](../../system/string/)) | ตั้งค่าของส่วนหัว 'From' |
| void [set_Host](./set_host/)([String](../../system/string/)) | ตั้งค่าของส่วนหัว 'Host' |
| void [set_IfModifiedSince](./set_ifmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าของส่วนหัว 'If-Modified-Since' |
| void [set_IfRange](./set_ifrange/)([System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\>) | ตั้งค่าของส่วนหัว 'If-Range' |
| void [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าของส่วนหัว 'If-Unmodified-Since' |
| void [set_MaxForwards](./set_maxforwards/)([Nullable](../../system/nullable/)\<**int32_t**\>) | ตั้งค่าของส่วนหัว 'Max-Forwards' |
| void [set_ProxyAuthorization](./set_proxyauthorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | ตั้งค่าของส่วนหัว 'Proxy-Authorization' |
| void [set_Range](./set_range/)([System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\>) | ตั้งค่าของส่วนหัว '[Range](../../system/range/)' |
| void [set_Referrer](./set_referrer/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ตั้งค่าของส่วนหัว 'Referer' |
| void [set_TransferEncodingChunked](./set_transferencodingchunked/)([Nullable](../../system/nullable/)\<**bool**\>) | ตั้งค่าที่บ่งบอกว่าค่าของส่วนหัว 'Transfer-Encoding' มี 'Chunked' หรือไม่ |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | รับส่วนหัวตามชื่อที่ระบุและตั้งค่าหรือเอาค่าของมันออก ค่า header จะถูกลบเมื่อพารามิเตอร์ 'value' เป็น nullptr มิฉะนั้นค่าที่แปรผลจะถูกตั้งค่า |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | รับส่วนหัวตามชื่อที่ระบุและตั้งค่าค่าที่แปรผลให้กับส่วนหัว |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่เป็น shared) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และส่งคืน ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดให้แปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | พยายามเพิ่มคู่ชื่อ-ค่าใหม่เข้าไปในคอลเลกชันปัจจุบัน |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | เพิ่มคอลเลกชันของคู่ชื่อ-ค่าเข้าไปในคอลเลกชันปัจจุบัน |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | พยายามรับค่าที่สอดคล้องตามชื่อที่ระบุ |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | พยายามแยกค่าที่ระบุและเพิ่มเข้าไปในค่าของส่วนหัว |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการนำไปใช้ของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการนำไปใช้ของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการนำไปใช้ของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการนำไปใช้ของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [HttpHeaders](../httpheaders/)
* เนมส페ซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)