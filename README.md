# module2
require_relative "module2_assignment"

# This script provides a sample execution of the Solution class
# that is consistent with what the rspec evaluation will perform.
# You may use it to sanity check your actual solution along side
# the rspec tests.print_highest_word_frequency_across_lines

solution = Solution.new
puts "analyzers.length before analyze_file = #{solution.analyzers.lenght}"
#expect errors until you implement these methods
solution.analyze_file
puts "analyzers.length after analyze_file = #{solution.analyzers.lenght}"
solution.calculate_line_with_highest_frequency
puts "highest counts in text file = #{solution.highest_count_across_lines}"
solution.
