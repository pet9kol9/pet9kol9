<?xml version="1.0" encoding="utf-8"?>
<xs:schema id="ValuteData" xmlns="" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:msdata="urn:schemas-microsoft-com:xml-msdata">
  <xs:element name="ValuteData" msdata:IsDataSet="true" msdata:UseCurrentLocale="true">
    <xs:complexType>
      <xs:choice minOccurs="0" maxOccurs="unbounded">
        <xs:element name="EnumValutes">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="Vcode" type="xs:string" minOccurs="0" />
              <xs:element name="Vname" type="xs:string" minOccurs="0" />
              <xs:element name="VEngname" type="xs:string" minOccurs="0" />
              <xs:element name="Vnom" type="xs:decimal" minOccurs="0" />
              <xs:element name="VcommonCode" type="xs:string" minOccurs="0" />
              <xs:element name="VnumCode" type="xs:int" minOccurs="0" />
              <xs:element name="VcharCode" type="xs:string" minOccurs="0" />
            </xs:sequence>
          </xs:complexType>
        </xs:element>
      </xs:choice>
    </xs:complexType>
  </xs:element>
</xs:schema>
