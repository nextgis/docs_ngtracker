

Setting up
=========================

After the app is installed to your device, you need to set it up to begin track recording.

.. _ngtr_set_record:

Track recording settings
-------------------------

When you open the app for the first time, give the following permissions:

* allow NextGIS Tracker to access location.

If you see the dialog shown on :numref:`ngtr_allow_location_pic`, select **Precise** and **While using app**.

.. figure:: _static/ngtr_allow_location_en.png
   :name: ngtr_allow_location_pic
   :align: center
   :width: 8cm

   Allow access to location

* in the newer Android version you also need to allow notifications from NextGIS Tracker.


.. _ngtr_set_send:

Setting up sending tracks to Web GIS
-------------------------------------

To upload tracks to your Web GIS (cloud-based or on-premise), set up synchronization.

In the top bar turn on **Sync with the cloud** switch (see :numref:`sync_with_cloud_pic`), then enter your Web GIS credentials and save, as shown on :numref:`webgis_creds_pic`.

.. figure:: _static/sync_with_cloud_main_en.png
   :name: sync_with_cloud_pic
   :align: center
   :width: 8cm

   Turning on synchronization

.. figure:: _static/webgis_creds_en.png
   :name: webgis_creds_pic
   :align: center
   :width: 8cm

   Entering Web GIS URL, login and password

When the settings are saved, you'll get a notification saying "Tracker is created". Under the "Sync" slider you'll see a message: "Automatically send tracking information to *Web GIS URL*", as shown on :numref:`synced_success_pic`.

.. figure:: _static/synced_created_en.png
   :name: synced_success_pic
   :align: center
   :width: 8cm

   Synchronization with Web GIS is enabled
