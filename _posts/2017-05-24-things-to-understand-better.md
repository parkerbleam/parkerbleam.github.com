# Linear Algebra

* Application of eigenvectors/values to PCA
* Matrices as transformations
* Develop matrix multiplication intution
* Dot/Cross/Inner products
* When to transpose (matrix mult. compatibility)
* Applied linear algebra in numpy
* L1 vs L2 distances and when to use each

# Deep Learning

* Recurrent Nerual Networks
* Convolutional Neural Networks
* word2vec and embedding space generally
* Long short-term memory
* Adversarial networks
* Using GPUs on AWS
* Implementations in Keras/TensorFlow

# Algorithms

* Time and space complexity
* Runtime analysis (Big O notation)
* BFS/DFS/Djikstra/A*
* Sorting

# Databases

* 1st - 3rd Normal Forms
* Why denormalization can be helpful
* Architectures of databases w/ pros cons
	* Elastic Search
	* mongoDB
	* postgres
	* Cassandra
* Indexes
	* Types (in SQL Server)
	* Storage/Speed tradeoffs
* OLAP

# High Performance Computing

* MapReduce/HFDS
* Sharding
* Spark

# Git

* Large File System (LFS)
	* Tracks on the server but not locally. A pointer to the file is stored locally and you can lazily access the data. An example use case could be storing models in .Rdata files.
* Put model results in commit messages so you can roll back to a specific model version
* 7-zip will split large files into 4 GB chunks and bring them back together seamlessly (helps with Box files size limitations on upload)
* Stash to temproarily store changes while getting back to clean via pull. Once clean can apply the stash and try pushing.
* Always merge onto the branch you are on. Merge develop into your feature branch to test that everything works. Then switch to develop and merge in your feature.
* Hotfix is fixing a bug on the master branch. This is done in live production level systems that are running on a server.
* Branches and pull requests are really the same thing. Pull requests are githubs way of handling contributions. A pull request starts with a fork which is a private branch on the official repository
* Rebasing linearizes the tree of commits


