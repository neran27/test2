test2
=====
Response

<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Body>
    <s:Envelope xmlns:s="http://www.w3.org/2003/05/soap-envelope" xmlns:a="http://www.w3.org/2005/08/addressing" xmlns:u="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd">
      <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
        <CheckAcctCNAEligibilityAndLockResponse xmlns="urn:MerrillLynch.Services">
          <CheckAcctCNAEligibilityAndLockResult>0</CheckAcctCNAEligibilityAndLockResult>
          <outputResponse xmlns:q1="urn:ML.App.DS.DataContracts.ProfileBusinessDataContracts" xsi:type="q1:CheckAcctCNAEligibilityAndLockResponse" Version="1.0">
            <q1:BusinessPayload>
              <q1:LockedAccounts>
                <q1:LockedAccount>
                  <q1:BUWTimestamp>{{BUWTimeStamp}}</q1:BUWTimestamp>
                  <q1:Capacity>JTWROS</q1:Capacity>
                  <q1:PartySequenceKey>1</q1:PartySequenceKey>
                  <q1:AccountUpdateEligibilityStatus>Y</q1:AccountUpdateEligibilityStatus>
                  <q1:AccountNameUpdateEligibilityStatus>Y</q1:AccountNameUpdateEligibilityStatus>
                  <q1:AccountMailingAddressUpdateEligibilityStatus>N</q1:AccountMailingAddressUpdateEligibilityStatus>
                  <q1:AddressChgLast30DaysInd>N</q1:AddressChgLast30DaysInd>
                  <q1:AMAcctInd>Y</q1:AMAcctInd>
                </q1:LockedAccount>
              </q1:LockedAccounts>
            </q1:BusinessPayload>
            <q1:StatusInfo>
              <StatusInfo xmlns="urn:ds-corecommondatacontracttype-v1">
                <Source>BPF</Source>
                <SourceDetail />
                <Code>ENT_DS_STD_000</Code>
                <TechnicalDescription>0000::SUCCESS</TechnicalDescription>
                <BusinessDescription>Success</BusinessDescription>
                <Severity />
              </StatusInfo>
            </q1:StatusInfo>
          </outputResponse>
        </CheckAcctCNAEligibilityAndLockResponse>
      </s:Body>
    </s:Envelope>
  </soap:Body>
  
  
  
  
  
  
  --------------------------------------------------------------------------------------------------------------------
  
  
  Loc
  
  
  <s:Envelope xmlns:s="http://www.w3.org/2003/05/soap-envelope" xmlns:a="http://www.w3.org/2005/08/addressing" xmlns:u="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd">
  <s:Header>
    <a:Action s:mustUnderstand="1">urn:MerrillLynch.Services/IProfileBusinessService/CheckAcctCNAEligibilityAndLockResponse</a:Action>
    <a:RelatesTo>urn:uuid:81d17af4-65a0-4422-9817-0e7832fc4f78</a:RelatesTo>
    <SYM xmlns="urn:MerrillLynch.Services" xmlns:i="http://www.w3.org/2001/XMLSchema-instance">
      <KeyValueOfstringstring xmlns="http://schemas.microsoft.com/2003/10/Serialization/Arrays">
        <Key>guid</Key>
        <Value>3afc44bf-34c0-42e2-813a-0e0782eebb72</Value>
      </KeyValueOfstringstring>
      <KeyValueOfstringstring xmlns="http://schemas.microsoft.com/2003/10/Serialization/Arrays">
        <Key>RootRequestSequence</Key>
        <Value>2</Value>
      </KeyValueOfstringstring>
    </SYM>
    <RootRequestSequence xmlns="urn:services-ml-com:extensibility-security">3</RootRequestSequence>
    <o:Security s:mustUnderstand="1" xmlns:o="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-secext-1.0.xsd">
      <u:Timestamp u:Id="_0">
        <u:Created>2014-10-06T05:00:34.280Z</u:Created>
        <u:Expires>2014-10-06T05:05:34.280Z</u:Expires>
      </u:Timestamp>
    </o:Security>
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <CheckAcctCNAEligibilityAndLockResponse xmlns="urn:MerrillLynch.Services">
      <CheckAcctCNAEligibilityAndLockResult>0</CheckAcctCNAEligibilityAndLockResult>
      <outputResponse xsi:type="q1:CheckAcctCNAEligibilityAndLockResponse" Version="1.0" xmlns:q1="urn:ML.App.DS.DataContracts.ProfileBusinessDataContracts">
        <q1:BusinessPayload>
          <q1:PartyId>
            <PartyIdTypeCode xmlns="urn:ds-corecommondatacontracttype-v1">MasterProfileId</PartyIdTypeCode>
            <PartyId xmlns="urn:ds-corecommondatacontracttype-v1">M007012572</PartyId>
          </q1:PartyId>
          <q1:BUWTimestamp>2014-10-06-01.00.34.272078</q1:BUWTimestamp>
          <q1:LockedAccounts>
            <q1:LockedAccount>
              <q1:AccountKeyData>
                <AccountId xmlns="urn:ds-corecommondatacontracttype-v1">882844530</AccountId>
                <AccountNumber xmlns="urn:ds-corecommondatacontracttype-v1">88Q11926</AccountNumber>
              </q1:AccountKeyData>
              <q1:Capacity>JTWROS</q1:Capacity>
              <q1:PartySequenceKey>1</q1:PartySequenceKey>
              <q1:AccountUpdateEligibilityStatus>Y</q1:AccountUpdateEligibilityStatus>
              <q1:AccountNameUpdateEligibilityStatus>Y</q1:AccountNameUpdateEligibilityStatus>
              <q1:AccountMailingAddressUpdateEligibilityStatus>N</q1:AccountMailingAddressUpdateEligibilityStatus>
              <q1:AddressChgLast30DaysInd>N</q1:AddressChgLast30DaysInd>
              <q1:AMAcctInd>Y</q1:AMAcctInd>
            </q1:LockedAccount>
          </q1:LockedAccounts>
        </q1:BusinessPayload>
        <q1:StatusInfo>
          <StatusInfo xmlns="urn:ds-corecommondatacontracttype-v1">
            <Source>BPF</Source>
            <SourceDetail>
            </SourceDetail>
            <Code>ENT_DS_STD_000</Code>
            <TechnicalDescription>0000::SUCCESS</TechnicalDescription>
            <BusinessDescription>Success</BusinessDescription>
            <Severity>
            </Severity>
          </StatusInfo>
        </q1:StatusInfo>
      </outputResponse>
    </CheckAcctCNAEligibilityAndLockResponse>
  </s:Body>
</s:Envelope>
</soap:Envelope>
