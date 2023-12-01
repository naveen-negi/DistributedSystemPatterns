# Distributed System Patterns Repository

This repository, [Distributed System Patterns](https://github.com/naveen-negi/DistributedSystemPatterns.git), contains the Distributed System Patterns project, including the `PhoneTagSaga` as a Git submodule.

## Cloning the Repository

To clone this repository along with its submodule (`PhoneTagSaga`), follow these steps:

### Using Git with Submodules

1. **Clone the Repository:**
    - Run the following command in your terminal to clone the repository along with the submodule:
      ```bash
      git clone --recursive https://github.com/naveen-negi/DistributedSystemPatterns.git
      ```

    - If you have already cloned the repository without the submodules, you can fetch the submodules using:
      ```bash
      git submodule init
      git submodule update
      ```

2. **Navigate to the Project Directory:**
    - Once the cloning is complete, change to the project directory:
      ```bash
      cd DistributedSystemPatterns
      ```

## Working with the Submodule

The `PhoneTagSaga` submodule, located at [PhoneTagSaga](https://github.com/naveen-negi/PhoneTagSaga.git), is a separate Git repository. To make changes or pull updates from this submodule, follow these steps:

1. **Navigate to the Submodule Directory:**
   ```bash
   cd PhoneTagSaga
