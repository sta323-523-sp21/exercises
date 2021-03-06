# STA 323 & 523: Exercises

All exercises along with their solutions.

| Topic                              | Exercises and solutions |
|------------------------------------|-------------------------|
| Introduction and Fundamentals of R | :white_check_mark:      |
| Vectors and functions              | :white_check_mark:      |
| Shell and version control          | :white_check_mark:      |
| Data structures and subsetting     | :white_check_mark:      |
| Object-oriented programming        | :white_check_mark:      |
| Data manipulation: dplyr           | :white_check_mark:      |
| Functionals                        | :white_check_mark:      |
| Statistical graphics with ggplot2  | :white_check_mark:      |
| Advanced visualizations            | :white_check_mark:      |
| String manipulation and regexes    | :white_check_mark:      |
| Spatial data visualization         | :white_check_mark:      |
| Spatial data wrangling             | :white_check_mark:      |
| Web scraping part I                | :white_check_mark:      |
| Web scraping part II               | :white_check_mark:      |
| Web APIs                           | :white_check_mark:      |
| make                               | :white_check_mark:      |
| Shiny part I                       |                         |
| Shiny part II                      |                         |
| Databases and SQL                  | :white_check_mark:      |
| SQLite, sqlite3, and more          | :white_check_mark:      |
| Memory and I/O                     | :white_check_mark:      |
| Parallelization                    | :white_check_mark:      |
| More parallelization and profiling | :white_check_mark:      |
| Futures and furrr                  |                         |
| Data bigger than RAM               |                         |
| Spark & sparklyr part I            |                         |
| Spark & sparklyr part II           |                         |

## Access

1. Fork this repository

2. Clone your forked repo

3. In your local repo, add a new remote associated with the location of the
   repo on GitHub that you forked
   ([sta323-523-sp21/exercises](https://github.com/sta323-523-sp21/exercises)). Give this new remote repo a nickname: `upstream`.
   ```bash
   git remote add upstream https://github.com/sta323-523-sp21/exercises.git
   ```

4. Verify that `upstream` has been added.
   ```
   git remote -v
   ```
5. As [sta323-523-sp21/exercises](https://github.com/sta323-523-sp21/exercises)
   is updated with new contents, update your local repo.
   ```
   git pull upstream main
   ```
