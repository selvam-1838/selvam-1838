class Selvaganapathi:
    def __init__(self):
        self.name              = "Selvaganapathi S"
        self.location           = "Chennai, Tamil Nadu, India"
        self.degree             = "B.E. Computer Science and Engineering"
        self.college             = "Chennai Institute of Technology (2024–28)"
        self.cgpa               = 7.6
        self.stack              = ["Python", "Java", "OpenCV", "YOLOv8", "AWS", "MongoDB"]
        self.currently_learning = ["Advanced Computer Vision", "Full-Stack Development"]
        self.fun_fact           = "Solved 500+ problems on LeetCode"
        self.hackathons         = ["Top 5 — Astrava Hackathon (AIT)"]

    def motto(self):
        return "Learn. Build. Ship. Repeat."

    def say_hi(self):
        print(f"Hey, I'm {self.name} — {self.motto()}")

me = Selvaganapathi()
me.say_hi()
