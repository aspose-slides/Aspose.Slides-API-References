---
title: "System::Xml"
second_title: Aspose.Slides C++ API 參考文件
description: 
type: docs
weight: 1119
url: /zh-hant/system.xml/
---
## 類別

| Class | Description |
| --- | --- |
| [Details_XmlException](./details_xmlexception/) | 返回有關最後例外的詳細資訊。 |
| [IApplicationResourceStreamResolver](./iapplicationresourcestreamresolver/) | 表示應用程式資源串流解析器。 |
| [IHasXmlNode](./ihasxmlnode/) | 允許類別從目前的上下文或位置返回一個 [XmlNode](./xmlnode/)。 |
| [IXmlLineInfo](./ixmllineinfo/) | 提供介面，使類別能返回行與位置資訊。 |
| [IXmlNamespaceResolver](./ixmlnamespaceresolver/) | 提供唯讀存取一組前置詞與命名空間對映。 |
| [NameTable](./nametable/) | 實作單執行緒的 [XmlNameTable](./xmlnametable/)。 |
| [XmlAttribute](./xmlattribute/) | 表示屬性。屬性的有效值與預設值於文件類型定義 (DTD) 或綱要中定義。 |
| [XmlAttributeCollection](./xmlattributecollection/) | 表示可依名稱或索引存取的屬性集合。 |
| [XmlCDataSection](./xmlcdatasection/) | 表示 CDATA 區段。 |
| [XmlCharacterData](./xmlcharacterdata/) | 提供多個類別使用的文字操作方法。 |
| [XmlCharType](./xmlchartype/) | 供內部使用。請勿直接使用此類別。 |
| [XmlComment](./xmlcomment/) | 表示 XML 註解的內容。 |
| [XmlConvert](./xmlconvert/) | 編碼與解碼 XML 名稱，並提供在執行階段類型與 XML [Schema](../system.xml.schema/) 定義語言 (XSD) 類型之間轉換的方法。轉換資料類型時，返回的值與區域設定無關。 |
| [XmlDeclaration](./xmldeclaration/) | 表示 XML 宣告節點 **<?xml version='1.0'...?>**。 |
| [XmlDocument](./xmldocument/) | 表示 XML 文件。您可以使用此類別來載入、驗證、編輯、加入及定位文件中的 XML。 |
| [XmlDocumentFragment](./xmldocumentfragment/) | 表示用於樹狀插入操作的輕量物件。 |
| [XmlDocumentType](./xmldocumenttype/) | 表示文件類型宣告。 |
| [XmlElement](./xmlelement/) | 表示元素。 |
| [XmlEntity](./xmlentity/) | 表示實體宣告，例如 **<!ENTITY... >**。 |
| [XmlEntityReference](./xmlentityreference/) | 表示實體參照節點。 |
| [XmlImplementation](./xmlimplementation/) | 定義一組 [XmlDocument](./xmldocument/) 物件的上下文。 |
| [XmlLinkedNode](./xmllinkednode/) | 返回緊接此節點之前或之後的節點。 |
| [XmlNamedNodeMap](./xmlnamednodemap/) | 表示可依名稱或索引存取的節點集合。 |
| [XmlNamespaceManager](./xmlnamespacemanager/) | 解析、加入與移除集合中的命名空間，並提供這些命名空間的範圍管理。 |
| [XmlNameTable](./xmlnametable/) | 原子化字串物件的表格。 |
| [XmlNode](./xmlnode/) | 表示 XML 文件中的單一節點。 |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/) | 提供 **XmlDocument::NodeChanged**、**XmlDocument::NodeChanging**、**XmlDocument::NodeInserted**、**XmlDocument::NodeInserting**、**XmlDocument::NodeRemoved** 與 **XmlDocument::NodeRemoving** 事件的資料。 |
| [XmlNodeList](./xmlnodelist/) | 表示有序的節點集合。 |
| [XmlNodeReader](./xmlnodereader/) | 表示讀取器，能在 [XmlNode](./xmlnode/) 中提供快速、非快取的單向前進 XML 資料存取。 |
| [XmlNotation](./xmlnotation/) | 表示註記宣告，例如 **<!NOTATION... >**。 |
| [XmlParserContext](./xmlparsercontext/) | 提供 [XmlReader](./xmlreader/) 解析 XML 片段所需的所有上下文資訊。 |
| [XmlProcessingInstruction](./xmlprocessinginstruction/) | 表示處理指示，XML 定義此指示以在文件文字中保留處理器特定資訊。 |
| [XmlQualifiedName](./xmlqualifiedname/) | 表示 XML 合格名稱。 |
| [XmlReader](./xmlreader/) | 表示讀取器，提供快速、非快取、單向前進的 XML 資料存取。 |
| [XmlReaderSettings](./xmlreadersettings/) | 指定在由 [XmlReader::Create](./xmlreader/create/) 方法建立的 [XmlReader](./xmlreader/) 物件上支援的一組功能。 |
| [XmlResolver](./xmlresolver/) | 解析以統一資源識別符 (URI) 命名的外部 XML 資源。 |
| [XmlSecureResolver](./xmlsecureresolver/) | 透過包裝 [XmlResolver](./xmlresolver/) 物件並限制底層 [XmlResolver](./xmlresolver/) 可存取的資源，協助保護 [XmlResolver](./xmlresolver/) 的其他實作。 |
| [XmlSignificantWhitespace](./xmlsignificantwhitespace/) | 表示混合內容節點中標記之間的空白或 **xml:space='preserve'** 範圍內的空白。此亦稱為顯著空白。 |
| [XmlText](./xmltext/) | 表示元素或屬性的文字內容。 |
| [XmlTextReader](./xmltextreader/) | 表示讀取器，提供快速、非快取、單向前進的 XML 資料存取。 |
| [XmlTextWriter](./xmltextwriter/) | 表示寫入器，提供快速、非快取、單向前進的方式產生符合 W3C 可擴充標記語言 (XML) 1.0 以及 XML 命名空間建議的 XML 資料串流或檔案。 |
| [XmlUrlResolver](./xmlurlresolver/) | 解析以統一資源識別符 (URI) 命名的外部 XML 資源。 |
| [XmlValidatingReader](./xmlvalidatingreader/) | 表示讀取器，提供文件類型定義 (DTD)、XML-Data Reduced (XDR) 綱要及 XML [Schema](../system.xml.schema/) 定義語言 (XSD) 驗證。 |
| [XmlWhitespace](./xmlwhitespace/) | 表示元素內容中的空白。 |
| [XmlWriter](./xmlwriter/) | 表示寫入器，提供快速、非快取、單向前進的方式產生包含 XML 資料的串流或檔案。 |
| [XmlWriterSettings](./xmlwritersettings/) | 指定在由 [XmlWriter::Create](./xmlwriter/create/) 方法建立的 [XmlWriter](./xmlwriter/) 物件上支援的一組功能。 |

## 函式

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | 比較兩個 [XmlQualifiedName](./xmlqualifiedname/) 物件。 |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | 比較兩個 [XmlQualifiedName](./xmlqualifiedname/) 物件。 |

## 列舉

| Enum | Description |
| --- | --- |
| [ConformanceLevel](./conformancelevel/) | 指定 [XmlReader](./xmlreader/) 與 [XmlWriter](./xmlwriter/) 物件執行的輸入或輸出檢查程度。 |
| [DtdProcessing](./dtdprocessing/) | 指定 DTD 處理的選項。[XmlReaderSettings](./xmlreadersettings/) 類別使用 DtdProcessing 列舉。 |
| [EntityHandling](./entityhandling/) | 指定 [XmlTextReader](./xmltextreader/) 或 [XmlValidatingReader](./xmlvalidatingreader/) 處理實體的方式。 |
| [Formatting](./formatting/) | 指定 [XmlTextWriter](./xmltextwriter/) 的格式化選項。 |
| [NamespaceHandling](./namespacehandling/) | 指定是否在 [XmlWriter](./xmlwriter/) 中移除重複的命名空間宣告。 |
| [NewLineHandling](./newlinehandling/) | 指定如何處理換行。 |
| [ReadState](./readstate/) | 指定讀取器的狀態。 |
| [XmlTokenizedType](./xmltokenizedtype/) | 表示字串的 XML 類型。此允許將字串讀取為特定的 XML 類型，例如 CDATA 區段類型。 |
| [ValidationType](./validationtype/) | 指定要執行的驗證類型。 |
| [WhitespaceHandling](./whitespacehandling/) | 指定空白的處理方式。 |
| [WriteState](./writestate/) | 指定 [XmlWriter](./xmlwriter/) 的狀態。 |
| [ExceptionType](./exceptiontype/) |  |
| [XmlDateTimeSerializationMode](./xmldatetimeserializationmode/) | 指定在字串與 [DateTime](../system/datetime/) 之間轉換時如何處理時間值。 |
| [XmlNamespaceScope](./xmlnamespacescope/) | 定義命名空間範圍。 |
| [XmlNodeChangedAction](./xmlnodechangedaction/) | 指定節點變更的類型。 |
| [XmlNodeOrder](./xmlnodeorder/) | 描述節點相對於第二個節點的文件順序。 |
| [XmlNodeType](./xmlnodetype/) | 指定節點的類型。 |
| [XmlOutputMethod](./xmloutputmethod/) | 指定序列化 [XmlWriter](./xmlwriter/) 輸出的方式。 |
| [XmlSpace](./xmlspace/) | 指定目前的 **xml:space** 範圍。 |
| [TriState](./tristate/) |  |
| [XmlStandalone](./xmlstandalone/) |  |

## 型別別名

| Typedef | Description |
| --- | --- |
| [XmlException](./xmlexception/) |  |
| [XmlNodeChangedEventHandler](./xmlnodechangedeventhandler/) | 表示處理 **XmlDocument::NodeChanged**、**XmlDocument::NodeChanging**、**XmlDocument::NodeInserted**、**XmlDocument::NodeInserting**、**XmlDocument::NodeRemoved** 與 **XmlDocument::NodeRemoving** 事件的方法。 |