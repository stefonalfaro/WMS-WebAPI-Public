# WMS-WebAPI-Public
.NET WebAPI backend for my Warehouse Management System


POST /api/api/Orders/4066 HTTP/1.1
Host: wms2.com
Content-Length: 1157
{"Status":"OPEN","Reference1":null,"Reference2":null,"CustomerPONumber":null,"POType":null,"DepositorOrderNumber":null,"WarehouseNotes":null,"InternalNotes":null,"OrderDate":"2022-02-02T23:21:48.898Z","RequestedShipDate":null,"ExpectedArrivalDate":null,"CancelDate":null,"ShipToCustomerId":3,"ShipToName":"SA Transports","ShipToAttention":null,"ShipToAddress1":"729 Essa Rd","ShipToCity":"Barrie","ShipToState":"ON","ShipToZip":"L4N 0T9","ShipToCountry":"Canada","ShipToContactName":"","ShipToContactEmail":"","ShipToContactPhone":"","ShipToDCNumber":null,"ShipToStoreNumber":null,"CustomerId":0,"BillOfLadingNumber":null,"CarrierVendorId":0,"CarrierName":null,"CarrierAddressLine1":null,"CarrierAddressLine2":null,"CarrierCity":null,"CarrierZip":null,"CarrierState":null,"CarrierCounty":null,"CarrierContactName":null,"CarrierContactEmail":null,"CarrierContactPhone":null,"CarrierSCAC":null,"CarrierTrackingNumber":null,"Weight":0,"OrderItems":[{"ItemId":9478,"OrderedQuantity":1,"UnitofMeasureId":5814,"UnitOfMeasureId":5814,"AutoAllocation":false},{"ItemId":9478,"OrderedQuantity":1,"UnitofMeasureId":5814,"UnitOfMeasureId":5814,"AutoAllocation":false}]}

DELETE /api/api/OrderItems/22887/5887 HTTP/1.1
Host: wms2.com

POST /api/api/Orders HTTP/1.1
Host: wms2.com
Content-Length: 652
{

    "Client":"1",

    "WarehouseID":"1",

    "PlacedByUserID":"1",

    "Reference1":"",

    "Reference2":"",

    "CustomerPONumber":"",

    "OrderDate":"12/1/20",

    "RequestedShipDate":"12/1/20",

    "ShipMethodOfPayment":"",

    "ShipToName":"Steve",

    "ShipToAttention":"",

    "ShipToAddress1":"6225 Kennedy Rd",

    "ShipToAddress2":"",

    "ShipToCity":"Mississauga",

    "ShipToZip":"L5T 2S8",

    "ShipToState":"Ontario",

    "ShipToCountry":"Canada",

    "ShipToContactName":"",

    "ShipToContactPhone":"",

    "ShipToContactEmail":"",

    "WarehouseNotes":"",

    "Weight":"500",

    "WeightUnitofMeasure":"LB"

}

POST /api/api/Orders/22878/Items HTTP/1.1
Host: wms2.com
Content-Length: 133

{

"VendorPartNumber":"",

"SKU":"Apple",

"OrderedQuantity":"100.0",

"UnitOfMeasure":"CASES",

"TrackingNumber":"",

"UCC128":""

}
