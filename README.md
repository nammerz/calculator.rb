calculator.rb
=============

p "whats yo first numba?!"
num1 = gets.chomp

p "whats that second numba yO?"
num2 = gets.chomp

p "Type 1 for addition, 2 for subtraction, 3 for multiplication, or division"
user_input = gets.chomp

if user_input == '1'
  answer = num1.to_i + num2.to_i
  elsif user_input == '2'
    answer = num1.to_i - num2.to_i
  elsif user_input == '3'
    answer = num1.to_i * num2.to_i
  elsif user_input == '4'
    answer = num1.to_f / num2.to_f
  end

puts "The answer is #{answer}. You couldn't figure this out in your head????"
