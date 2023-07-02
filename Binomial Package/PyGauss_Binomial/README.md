# PyGauss_Binomial

PyGauss_Binomial is a Python package that provides functionality for working with probability distributions. It includes classes for the Gaussian and Binomial distributions, along with general distribution calculations and visualizations.

## Installation

To install PyGauss_Binomial, simply use pip:


pip install PyGauss_Binomial


## Gaussian Distribution

The Gaussian class in PyGauss_Binomial represents a Gaussian distribution, also known as a normal distribution. It allows you to calculate and visualize the properties of the distribution, including mean, standard deviation, probability density function, and more.

### Example Usage:

python
from pygauss_binomial import Gaussian

# Create a Gaussian distribution with mean 0 and standard deviation 1
gaussian = Gaussian(0, 1)

# Calculate the mean and standard deviation
mean = gaussian.calculate_mean()
stdev = gaussian.calculate_stdev()

# Plot a histogram of the data
gaussian.plot_histogram()

# Plot the probability density function
gaussian.plot_histogram_pdf()


## Binomial Distribution

The Binomial class represents a binomial distribution, which models the probability of a certain number of successes in a fixed number of independent trials. It provides methods for calculating the mean, standard deviation, probability density function, and visualizing the distribution.

### Example Usage:

python
from pygauss_binomial import Binomial

# Create a binomial distribution with probability 0.5 and number of trials 10
binomial = Binomial(0.5, 10)

# Calculate the mean and standard deviation
mean = binomial.calculate_mean()
stdev = binomial.calculate_stdev()

# Plot a bar chart of the distribution
binomial.plot_bar()

# Plot the probability density function
binomial.plot_bar_pdf()


## General Distribution

The Distribution class is a generic distribution class that serves as the base for the Gaussian and Binomial distributions. It provides basic functionality for reading data from a file and contains common attributes and methods shared by the derived distributions.

### Example Usage:

python
from pygauss_binomial import Distribution

# Create a generic distribution with mean 0 and standard deviation 1
distribution = Distribution(0, 1)

# Read data from a file
distribution.read_data_file('data.txt')

# Calculate the mean and standard deviation
mean = distribution.calculate_mean()
stdev = distribution.calculate_stdev()


## Contribution

Contributions to PyDist are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the GitHub repository: [https://github.com/mohaomar495/Python_projects](https://github.com/mohaomar495/Python_projects)

## License

PyDist is licensed under the MIT License. See the [LICENSE](https://github.com/mohaomar495/Binomial\Package/PyGauss_Binomial/license.txt) file for more details.
