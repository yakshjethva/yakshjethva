```php
<?php

namespace yakshjethva;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Actively looking to join',
                'position' => ''         
            ]
        ];
    }

    public function getPreviousWorkplace(): array
    {
        return [
            'workplace' => [
                'name' => 'Briskstar',
                'course' => 'PHP/WordPress Developer'         
            ]
        ];
    }

    public function getCurrentEducation(): array
    {
        return [
            'education' => [
                'name' => 'Fanshawe College',
                'course' => 'Mobile Application Development'         
            ]
        ];
    }

    
    
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Angular::class,
            Codeigniter::class,
            Aws::class,
            MySQL::class,
            NodeJS::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To work on an open source project';
    }
}
```
