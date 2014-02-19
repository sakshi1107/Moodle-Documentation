.. header:: Sphinx and Read the docs test.

.. contents:: Table of Contents
   :depth: 2


.. raw:: html

        <iframe width="420" height="315" src="http://www.youtube.com/embed/NvoJ31F0Y8E" frameborder="0" allowfullscreen></iframe>


Simple Documentation Tutorials : Moodle-Docs 2.5
=================================================

Another Simple header 2.5
==========================

Here is some :term:`text` explaining some very :term:`complicated` stuff.::
       
    print 'hello'
    >> hello

Guide
^^^^^
.. toctree::
   :maxdepth: 2

   helps
   About license <license>
   contact
   Glossary

Indices and tables 2.5
=======================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Refer other related doc of :ref:`license <license>` 

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

1. This is a  *numbered* list.
2. It has two items too.

#. This is a **numbered** list.
#. It has two items too.

.. image:: images/logo.jpg
   :height: 150px
   :width: 200px
   :alt: moodle logo
   :align: right
   :target: http://moodle.org/

.. figure:: images/logo.jpg
   :scale: 50 %
   :alt: map to buried treasure

   This is the caption of the figure (a simple paragraph).

   The legend consists of all elements after the caption.  In this
   case, the legend consists of this paragraph and the following
   table:

   +------------------------------+-----------------------+
   | Symbol                       | Meaning               |
   +==============================+=======================+
   | .. image:: images/tent.jpg   | Campground            |
   +------------------------------+-----------------------+
   | .. image:: images/waves.jpg  | Lake                  |
   +------------------------------+-----------------------+

.. topic:: Topic Title      
   
   Subsequent indented lines comprise     
   the body of the topic, and are     
   interpreted as body elements.

.. sidebar:: Sidebar Title
   :subtitle: Optional Sidebar Subtitle

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.

"To Ma Own Beloved Lassie: A Poem on her 17th Birthday", by
Ewan McTeagle (for Lassie O'Shea):

    .. line-block::

        Lend us a couple of bob till Thursday.
        I'm absolutely skint.
        But I'm expecting a postal order and I can pay you back
            as soon as it comes.
        Love, Ewan.


.. parsed-literal::

   ( (title_, subtitle_?)?,
     decoration_?,
     (docinfo_, transition_?)?,
     `%structure.model;`_ )


.. compound::

   The 'rm' command is very dangerous.  If you are logged
   in as root and enter ::

       cd /
       rm -rf *

   you will erase the entire contents of your file system.


.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"


.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!










.. footer:: Sphinx and Read the docs test.
 Learning concept of sphinx and read the docs end.

















