# objects-for-lookups
// Setup
function phoneticLookup(val) {
  var result = "";

  // Only change code below this line
  var lookup = {
    "alpha": "Adams",
    "bravo": "Boston",
    "charlie": "Chicago",
    "delta": "Denver",
    "echo": "Easy",
    "foxtrot": "Frank",
  }
  result = lookup[val] //result holds the value of val
  
  return result;
}

// Change this value to test
console.log(phoneticLookup("charlie"));
