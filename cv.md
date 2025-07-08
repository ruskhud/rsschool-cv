# Ruslan Khudaiberdin
# My Contact Info:
* Phone: +79129136510
* E-mail: ruskhud@gmail.com
* GitHub: ruskhud
# About Me
I'm work in generating company as an expert in commercial electricity metering. I like to study new interesting stuffs like programming. I'd like to get knowledge and skills that will be enough for employment in a company. 
# Skills:
* HTML&CSS
* C#
* Python
* Git/GitHub
# Code Example:
~~~
namespace Mazes
{
    public static class EmptyMazeTask
    {
        public static void MoveOut(Robot robot, int width, int height)
        {
            MoveDown(robot, height);
            MoveRight(robot, width);
        }

        public static void MoveDown(Robot robot, int down)
        {
            for (int i = 0; i < down - 3; i++)
                robot.MoveTo(Direction.Down);
        }

        public static void MoveRight(Robot robot, int width)
        {
            for (int i = 0; i < width - 3; i++)
                robot.MoveTo(Direction.Right);
        }
    }
} 
~~~
