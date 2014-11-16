:title: Logging In
:description: Logging in to your cluster.

.. _logging_in:

Logging In
==========

For some tasks you need to log in to your cluster; for example creating fleet service units (via ``fleetctl``).

Deis runs on CoreOS so connecting is as simple as connecting to CoreOS via SSH.

CoreOS's default username is ``core``. Use the SSH key you provisioned the cluster with.

Find the public IP address of one of your nodes (or use "convience" DNS records if you've set them up).

.. code-block:: console

    $ ssh core@104.131.93.162 -i ~/.ssh/deis.pub

You should now be logged into one of your cluster's nodes and able to interact directly.
