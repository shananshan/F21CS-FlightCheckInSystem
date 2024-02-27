# ArrayList<> or HashMap<String, Object>
* For statistical operations, such as calculating the sum of a parameter, use ArrayList<>. More convenient. This is because ArrayList allows storing passenger information in order, and it is easy to iterate over all passengers to perform statistical operations.
* Using HashMap<String, Object> A more complex operation is required, because in the HashMap, the passenger information is stored as key-value pairs rather than in order. To compute the sum, you need to iterate over all the key-value pairs, extract the parameter you want to count from each value, and add it up. Such an operation is relatively tedious and may require more code.
