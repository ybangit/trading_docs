stock_price_analytics
=====

.. autosummary::s
   :toctree: generated

   lumache




.. _installation:

システムトレードに向けた株価チャートの見方と値動きの仕組み
------------

まだ株価の値動きに対する知識がない方向けに、
システムトレードを作るにあたり、どのように株価やテクニカルを見ればよいかを
経験則・発見的な進め方で説明します。



.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

