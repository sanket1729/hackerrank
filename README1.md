# hackerrank
hackerrank codes
<stix:STIX_Package 
	xmlns:AddressObj="http://cybox.mitre.org/objects#AddressObject-2"
	xmlns:cybox="http://cybox.mitre.org/cybox-2"
	xmlns:ds="http://www.w3.org/2000/09/xmldsig#"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xmlns:stix="http://stix.mitre.org/stix-1"
	xmlns:ttp="http://stix.mitre.org/TTP-1"
	xmlns:xs="http://www.w3.org/2001/XMLSchema"
	xmlns:stixCommon="http://stix.mitre.org/common-1"
	xmlns:example="http://example.com"
	xmlns:cyboxCommon="http://cybox.mitre.org/common-2"
	xmlns:xlink="http://www.w3.org/1999/xlink"
	 id="example:Package-8718311d-58e6-4419-8858-30836491f38c" version="1.2">
    <stix:Observables cybox_major_version="2" cybox_minor_version="1" cybox_update_version="0">
        <cybox:Observable id="example:Observable-ecea043e-2aff-4863-8dcc-d79b49786954">
            <cybox:Object id="example:Address-cd7df285-eda3-4af3-a851-466ee12dd389">
                <cybox:Properties xsi:type="AddressObj:AddressObjectType" category="ipv4-addr">
                    <AddressObj:Address_Value>198.51.100.2</AddressObj:Address_Value>
                </cybox:Properties>
            </cybox:Object>
        </cybox:Observable>
        <cybox:Observable id="example:Observable-03e29834-6f96-4830-bf09-06bf64671499">
            <cybox:Object id="example:Address-5c2fe66e-692f-48b3-8363-5f8e88725fc2">
                <cybox:Properties xsi:type="AddressObj:AddressObjectType" category="ipv4-addr">
                    <AddressObj:Address_Value>198.51.100.17</AddressObj:Address_Value>
                </cybox:Properties>
            </cybox:Object>
        </cybox:Observable>
        <cybox:Observable id="example:Observable-f99baab1-94c7-4651-9406-a1cafa234f63">
            <cybox:Object id="example:Address-c8f25ece-cabb-4f5c-8e80-3dcd2e662de5">
                <cybox:Properties xsi:type="AddressObj:AddressObjectType" category="ipv4-addr">
                    <AddressObj:Address_Value>203.0.113.19</AddressObj:Address_Value>
                </cybox:Properties>
            </cybox:Object>
        </cybox:Observable>
    </stix:Observables>
    <stix:TTPs>
        <stix:TTP id="example:ttp-3d3d7749-5307-4c68-aac8-41741adba8b6" timestamp="2016-11-02T07:06:51.636309+00:00" xsi:type='ttp:TTPType'>
            <ttp:Title>Malware C2 Channel</ttp:Title>
            <ttp:Resources>
                <ttp:Infrastructure>
                    <ttp:Type>Malware C2</ttp:Type>
                    <ttp:Observable_Characterization cybox_major_version="2" cybox_minor_version="1" cybox_update_version="0">
                        <cybox:Observable idref="example:Observable-ecea043e-2aff-4863-8dcc-d79b49786954">
                        </cybox:Observable>
                        <cybox:Observable idref="example:Observable-03e29834-6f96-4830-bf09-06bf64671499">
                        </cybox:Observable>
                        <cybox:Observable idref="example:Observable-f99baab1-94c7-4651-9406-a1cafa234f63">
                        </cybox:Observable>
                    </ttp:Observable_Characterization>
                </ttp:Infrastructure>
            </ttp:Resources>
        </stix:TTP>
    </stix:TTPs>
</stix:STIX_Package>
