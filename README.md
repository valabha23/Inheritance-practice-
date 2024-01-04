//practice 1
contract SimpleStorage
 {
    //this will get initiallized to 0
    uint256 public favoriteNumber ;

    function store(uint256 _favoriteNumber) public {
        favoriteNumber = _favoriteNumber;
    }

 }
    
