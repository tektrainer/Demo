#############
Heading 1
#############

*************
Heading 2
*************

===========
Heading 3
===========

#. Review your entry to verify that the key is accurate and that it is
   surrounded by quotation marks. If there is a list of keys, they must be
   comma separated.

   * In this example, the key for the Annotation Problem tool is the only
     value in the list.

   * In this example, the key for the Annotation Problem tool is added at
     the beginning of a list of other keys.

#. Select **Save Changes**.

#. In the ``lms.env.json`` and ``cms.env.json`` files, set the value of
   ``CERTIFICATES_HTML_VIEW`` within the ``FEATURES`` object  to ``true``.

   .. code-block:: bash

     "FEATURES": {
         ...
         'CERTIFICATES_HTML_VIEW': true,
         ...
     }

#. Save the ``lms.env.json`` and ``cms.env.json`` files.
