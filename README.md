### About

Collection of the different sort of own data analysis performed with help of RapidMiner tool.

Collection of the different sort of own data analysis performed with help of IPython and it's amazing Notebook (now known as [Jupyter Notebook](http://jupyter.org/)).

### Dependencies

* [RapidMiner Studio 5.](https://github.com/rapidminer/rapidminer-5)

### Installing Rapidminer from Sources

You need to have [Ant](http://ant.apache.org/), [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and [Git](https://git-scm.com/) installed. Not this is is to installed RapidMiner 5.

```bash
git clone https://github.com/rapidminer/rapidminer-5.git
cd rapidminer-5
ant build
ant release.makePlatformIndependent
cd scripts
RapidMinerGUI 
```

### Data Analysis

* [salary_example](salary_example)
    - Example done in Rapidminer based on [article](http://habrahabr.ru/post/269427/). You need to import 'employee_salary.rm' file *File -> Import Process*.

### Author

* Viktor Dmitriyev