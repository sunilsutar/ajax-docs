---
title: Telerik.Web.UI.RadProgressManager
page_title: Client-side API Reference
description: Client-side API Reference
---

# Telerik.Web.UI.RadProgressManager  : Telerik.Web.UI.RadWebControl

## Methods

###  startAsyncPolling

Explicitly starts the polling to the server.

#### Parameters

#### Returns

`None` 

###  stopAsyncPolling

Explicitly stops the polling to the server.

#### Parameters

#### Returns

`None`

## Events

### clientProgressStarted 

Occurs when the RadProgressManager starts monitoring progress. 

#### Event Data

##### sender `Telerik.Web.UI.RadProgressManager`

The instance of the RadProgressManager raised the event.

##### args `Sys.EventArgs`

The event arguments.  

### clientProgressUpdating

Occurs when a RadProgressArea dialog is about to update one of its progress bars.

#### Event Data

##### sender `Telerik.Web.UI.RadProgressManager`

The instance of the RadProgressManager raised the event.

##### args `Sys.EventArgs`

The event arguments.  

### clientSubmitting

Occurs after the RadProgressManager has been fully initialized on the client-side.

#### Event Data

##### sender `Telerik.Web.UI.RadCloudUpload`

The instance of the RadProgressManager raised the event.

##### args `Sys.CancelEventArgs`

The event arguments.  