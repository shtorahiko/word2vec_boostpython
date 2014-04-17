# word2vec_boostpython

word2vec binding for Python using Boost.Python

Its goal: good wrapper to easily handle vectors which were created by word2vec.
For example, `get_vectors` returns Numpy's ndarray.

Original C implementation: https://code.google.com/p/word2vec/

Code License: Apache License 2.0 (same to original project)


## How to use

You need to fix some hard-coded config. If you know how to automate this, please help me.

path to boost in Jamroot:

    use-project boost
      : /home/nishio/boost_1_55_0 ;

path to boost tools in boost-build:

    boost-build /home/nishio/boost_1_55_0/tools/build/v2 ;

Then run $ <bjam_path>/bjam

