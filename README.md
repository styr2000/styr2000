```php
<?php
namespace Styr;


class Styr
{
    private $lookingJob = true;

    public function index();
    {
        if($this->lookingJob) {
            return $this->tech();
        } else {
            return "Got hired!";
        }
    }

    public tech(){
        return = [
              Laravel::class,
              Python::class,
              Mysql::class,
              Nginx::class,
              AndroidStudio::class
        ];
    }


}
