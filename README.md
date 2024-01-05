# Move Badminton

## Objectives

Move.Badminton คือ Badminton service ของโครงการ Move พัฒนาด้วย .NET 8.0

## Source code structures

- **Move.Badminton.Domain** project
    > Class library สำหรับ entities, interfaces ของ Badmin
- **Move.Badminton.Business** project
    > Class library สำหรับ business logic ของ Badminton เช่น การสร้าง การแก้ไข การลบ ทีม, แมตช์การแข่งขัน
- **Move.Badminton.Infrastructure** project
    > Class library สำหรับ infrastructure ของ Badminton เช่น repositories, messages, databases
- **Move.Badminton.Api** project
    > Web Api ของ Badminton