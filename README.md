# TallyConnector-CharteredAccountant
This is a Paid version of TDL for Chartered Accountants 


TDL Order and Preview of data is [Here](https://docs.google.com/forms/d/e/1FAIpQLSe_MLymF1eeP1EBItPzBizqOcOZ1Fm-xTPFxHZTIu4PzycZRg/viewform)

This TDL Helps to Get Around 90 % of the Data in Tally to Excel in quick seconds



**The Following are the fields available in each table**

> [NOTE]

## Table Name:Ledger

To Read [more](https://techca.app/viewtopic.php?t=28)  and discuss on this logon to 

Sheet Name: Ledger_forensics



![image](https://github.com/ramajayam-CA/TallyConnector-CharteredAccountant/assets/12751693/06b1b578-2239-4d1e-902a-dc73201ead79)



### Query to Get the Data  (Copy and paste the code in the calculator Panel)


****




<p><b>Select $Name, $Createdby, $CreatedDate, $Masterid, $Alterid, $Alteredon, $Alteredby, $Updateddatetime, $LastVoucherDate, $Parent, $$AscrAmt:$openingBalance, $$AscrAmt:$_ClosingBalance from ledger order by $Alterid desc</b> </p>


## Table Name:A__Ledger10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)


<p><b>Select $Name, $_PrimaryGroup, $Parent, $OpeningBalance, $ClosingBalance, $_PrevYearBalance, $IsRevenue, $PartyGSTIN, $MasterId, $AlterID, $Nature_Led, $UpdatedDate, $UpdatedTime, $CreatedBy, $CreatedDate, $AlteredDate, $AlteredBy, $LastVoucherDate, $Total_Debit, $Total_Credit, $GSTDutyHead, $PAN, $BillRef, $OnAccValue, $OverdueBills, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__Ledger10</b> </p>


## Table Name:A__T_Vch10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)

<p><b>Select $Key, $MasterId, $AlterID, $VoucherNumber, $Date, $VoucherTypeName, $VchTypeParent, $Led_Lineno, $Type, $Particulars, $Amount, $Debit, $Credit, $Led_Parent, $Led_Group, $Party_LedName, $Vch_GSTIN, $Led_GSTIN, $GSTIN_Check, $Led_PAN, $Party_GST_Type, $GST_Classification, $Narration, $Vendor_Inv_Number, $Vendor_Inv_Date, $EnteredBy, $AlteredBy, $AlteredOn, $UpdatedDate, $UpdatedTime, $Nature_Led, $Is_Debit, $HasBankEntry, $CashBank_Credited, $CashBank_Debited, $HasCashFlow, $IsCashBankAcct, $AffectsInventory, $Led_MID, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__T_Vch10</b> </p>


## Table Name:A__M_ClBill_11


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<b> <p>Select $Key, $BillName, $LedName, $BillDate, $OpeningBalance, $ClosingBalance, $billcreditper, $AdvanceBill, $IsCleared, $LedMid, $LedAltid, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__M_ClBill_11</b> </p>

## Table Name:A__M_OpBill_11


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Key, $BillName, $LedName, $BillDate, $OpeningBalance, $ClosingBalance, $billcreditper, $AdvanceBill, $IsCleared, $LedMid, $LedAltid, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__M_OpBill_11</b> </p>


## Table Name:A__T_Bill_11


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Key, $MasterId, $AlterID, $VoucherTypeName, $VoucherTypeParent, $VoucherNumber, $Led_Lineno, $Type, $Particulars, $Amount, $Led_amt, $Led_Masterid, $VchDate, $PartyLedgerName, $PartyName, $_LedgerName, $BilRef, $BilType, $BillAmt, $billcreditper, $LineNo, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__T_Bill_11</b> </p>


## Table Name:A___M_LedKey


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Key, $MasterId, $AlterID, $VoucherNumber, $Date, $VoucherTypeName, $VchTypeParent FROM A___M_LedKey </b> </p>


## Table Name:A__M_GSTIN11


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Name, $Gst, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__M_GSTIN11</b> </p>


## Table Name:A__M_Stock10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $MasterId, $AlterID, $Name, $PartnoParent, $Category, $OpeningBalance, $ClosingBalance, $ClosingRate, $ClosingValue, $LastPurcCost, $LastPurcDate, $LastPurcParty, $LastPurcPrice, $LastPurcQty, $LastSaleDate, $LastSaleParty, $LastSaleQty, $LastVoucherDate, $EnteredBy, $GSTTypeofSupply, $CostingMethod, $ValuationMethod, $BaseUnits, $AdditionalUnits, $_HSNCode, $_IntegratedTax, $_CentralTax, $_StateTax, $_HSNDescription, $_InwardQuantity, $_InwardValue, $_OutwardQuantity, $_OutwardValue, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__M_Stock10</b> </p>


## Table Name:A__T_BatchAllocations10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Key, $VoucherNumber, $Date, $VoucherTypeName, $VchTypeParent, $OrderNo, $TrackingNumber, $Amount, $ActualQty, $StockItemName, $Rate_Head, $Amount_Head, $ACTUALQTY_Head, $UOM, $Lineno, $Party_LedName, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__T_BatchAllocations10</b> </p>


## Table Name:A__T_EwayBill10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Key, $VoucherNumber, $Date, $VoucherTypeName, $VchTypeParent, $BillDate, $BillNumber, $BillStatus, $CancelCode, $CancelReason, $DocumentType, $GeneratedOn, $SubType, $UpdatedDate, $Validity, $ConsigneeAddress, $ConsigneeName, $ConsigneeGSTIN, $Consigneepincode, $ConsigneestateName, $ConsignorGSTIN, $ConsignorName, $ConsignorPlace, $ConsignorPincode, $ConsolidatedBillNumber, $ConsolidatedBillDate, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__T_EwayBill10



## Table Name:A__T_HSN10


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
**Select $Key, $VoucherNumber, $Date, $VoucherTypeName, $VchTypeParent, $Led_Lineno, $PlaceOfSupply, $PartyLedgerName, $PartyGSTIN, $IRN, $IRNAckNo, $StockItemName, $HSNSourceType, $GSTOvrdnTaxability, $GSTOvrdnTypeOfSupply, $GSTHSNName, $Rate, $ActualQty, $Amount, $UOM, $IsDebit, $StockMid, $Head_Name, $Head_With_rate, $Inv_Lineno, $GST_Rate, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__T_HSN10</b> </p>

## Table Name:AA_T__GSTSheet


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $MKey, $Date, $Vch_Type_Parent, $Vendor_Invoice_Number, $Vendor_Invoice_Date, $MVoucher_Number, $TTV_Revenue, $TTV_BalanceSheet, $CgTax, $SgTax, $IgTax, $CessTax, $Vendor_CustomerName, $Vch_GSTIN, $Led_GSTIN, $PlaceOfSupply, $COMPANY_GSTIN FROM AA_T__GSTSheet</b> </p>


## Table Name:A__1__Audit


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
<p><b>Select $Name, $Parent, $_PrimaryGroup, $OpeningBalance, $ReceiptAmt, $PaymentAmt, $SalesAmt, $PurchaseAmt, $CreditNAmt, $DebitNAmt, $JournalAmt, $ClosingBalance FROM A__1__Audit</b> </p>


## Table Name:A__DayBK_FC


### Query to Get the Data  (Copy and paste the code in the calculator Panel)
 <p><b>Select $Key, $MasterId, $AlterID, $VoucherNumber, $Date, $VoucherTypeName, $Led_Lineno, $Type, $LedgerName, $Amount, $Currency, $ForexValue, $Fx_Rate, $Led_Parent, $Led_Group, $Party_LedName, $Vch_GSTIN, $Led_GSTIN, $Party_GST_Type, $GST_Classification, $Narration, $EnteredBy, $LastEventinVoucher, $UpdatedDate, $UpdatedTime, $Nature_Led, $Led_MID, $CompanyName, $Year_from, $Year_to, $Company_number, $Path FROM A__DayBK_FC</b> </p>

## Table Name:GST single Sheet




# Future ideas

- [ ] Get some more fields useful for audit
- [ ] 



